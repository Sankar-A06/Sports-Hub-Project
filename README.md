# FitTracker Pro 🏋️‍♂️

[![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-green.svg)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-4.18+-blue.svg)](https://expressjs.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**FitTracker Pro** is a comprehensive fitness and workout management platform designed to help users track their fitness journey, monitor progress, and achieve their health goals with precision.

## 🌟 Features

- **Workout Management**: Create, join, and manage fitness sessions
- **Progress Tracking**: Monitor your fitness journey with detailed analytics
- **Community Features**: Connect with fellow fitness enthusiasts
- **Real-time Updates**: Live session updates and notifications
- **User Authentication**: Secure signup/signin with JWT tokens
- **Admin Panel**: Comprehensive management tools for administrators
- **Responsive Design**: Beautiful UI that works on all devices
- **Role-based Access**: Player/Admin role management

## 🚀 Live Demo

- **Production**: [Coming Soon]
- **Staging**: [Coming Soon]

## 📸 Screenshots

![Homepage](screenshots/homepage.png)
![Workouts](screenshots/workouts.png)
![Progress](screenshots/progress.png)

## 🛠️ Quick Start

### Prerequisites

- Node.js 18+ 
- MongoDB 6.0+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sankar-A06/Sports-Hub-Project.git
   cd Sports-Hub-Project
   ```

2. **Install dependencies**
   ```bash
   npm run install-all
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env
   # Edit .env with your MongoDB connection string and JWT secret
   ```

4. **Start the application**
   ```bash
   npm run dev
   ```

5. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 🚀 Deployment

### One-Click Deploy

[![Deploy to Heroku](https://img.shields.io/badge/Deploy%20to%20Heroku-430098?style=for-the-badge&logo=heroku)](https://heroku.com/deploy?template=https://github.com/Sankar-A06/Sports-Hub-Project)

[![Deploy to Vercel](https://img.shields.io/badge/Deploy%20to%20Vercel-000000?style=for-the-badge&logo=vercel)](https://vercel.com/new/clone?repository-url=https://github.com/Sankar-A06/Sports-Hub-Project)

[![Deploy to Railway](https://img.shields.io/badge/Deploy%20to%20Railway-0B0D0E?style=for-the-badge&logo=railway)](https://railway.app/template/your-template-id)

### Manual Deployment

1. **Prepare for production**
   ```bash
   npm run build
   ```

2. **Set environment variables**
   - `NODE_ENV=production`
   - `MONGODB_URI=your_mongodb_connection_string`
   - `JWT_SECRET=your_jwt_secret`

3. **Deploy to your preferred platform**
   - Heroku: Use the included `Procfile`
   - Vercel: Use the included `vercel.json`
   - Railway: Use the included `railway.json`

## 📚 Documentation

- **[Complete Module Documentation](docs/COMPLETE_MODULE_DOCUMENTATION.txt)** - Detailed technical documentation
- **[Deployment Guide](docs/DEPLOYMENT_GUIDE.md)** - Production deployment instructions
- **[MongoDB Atlas Setup](docs/MONGODB_ATLAS_SETUP.md)** - Database setup guide
- **[GitHub Deployment Guide](docs/GITHUB_DEPLOYMENT_GUIDE.md)** - GitHub-specific deployment

## 🏗️ Technology Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication
- **bcrypt** - Password hashing
- **CORS** - Cross-origin resource sharing

### Frontend
- **HTML5** - Markup
- **CSS3** - Styling with glassmorphism design
- **Vanilla JavaScript** - Client-side logic
- **Font Awesome** - Icons
- **Responsive Design** - Mobile-first approach

### DevOps
- **Git** - Version control
- **GitHub Actions** - CI/CD
- **Docker** - Containerization (optional)
- **Heroku/Vercel/Railway** - Deployment platforms

## 🔌 API Endpoints

### Authentication
- `POST /api/auth/signup` - User registration
- `POST /api/auth/signin` - User login
- `POST /api/auth/change-password` - Change password

### Workouts
- `GET /api/sessions` - Get all workouts
- `POST /api/sessions` - Create new workout
- `PUT /api/sessions/:id` - Update workout
- `DELETE /api/sessions/:id` - Delete workout

### Admin
- `GET /api/admin/users` - Get all users
- `GET /api/admin/sessions` - Get all sessions
- `DELETE /api/admin/users/:id` - Delete user

## 📖 Usage Guide

### For Users
1. **Sign Up**: Create your account
2. **Browse Workouts**: Explore available fitness sessions
3. **Join Sessions**: Participate in workouts
4. **Track Progress**: Monitor your fitness journey
5. **Create Workouts**: Host your own fitness sessions

### For Administrators
1. **User Management**: Manage user accounts
2. **Session Oversight**: Monitor all workouts
3. **Content Moderation**: Ensure community guidelines
4. **Analytics**: View platform statistics

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

Found a bug? Please report it using our [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributors

- **Sankar** - *Initial work* - [Sankar-A06](https://github.com/Sankar-A06)

## 🙏 Acknowledgments

- Font Awesome for the amazing icons
- MongoDB Atlas for database hosting
- The open-source community for inspiration

## 💬 Support

- **Discord**: [Join our community](https://discord.gg/your-discord)
- **Email**: support@fittrackerpro.com
- **Issues**: [GitHub Issues](https://github.com/Sankar-A06/Sports-Hub-Project/issues)

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Sankar-A06/Sports-Hub-Project&type=Date)](https://star-history.com/#Sankar-A06/Sports-Hub-Project&Date)

---

⭐ **Star this repository if you found it helpful!**