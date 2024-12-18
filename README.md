# X Dating App

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-In%20Development-brightgreen)](https://github.com/tony-42069/x-dating-app)
[![Node](https://img.shields.io/badge/Node-v18+-blue)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)

A modern dating application that leverages X (Twitter) data and xAI to create meaningful connections based on users' digital footprints and interactions.

## 🌟 Features

- **AI-Powered Matching**: Utilizes xAI for intelligent profile analysis and compatibility matching
- **X Integration**: Analyzes user interactions, interests, and engagement patterns from X
- **Smart Recommendations**: Suggests potential matches based on:
  - Tweet content and topics
  - Interaction patterns
  - Shared interests
  - Engagement behavior
- **Privacy-First**: Robust data protection and user consent management
- **Real-time Chat**: Integrated messaging system for matched users
- **Intuitive Interface**: Modern, swipe-based user experience

## 🛠️ Tech Stack

### Frontend
- React with TypeScript
- Tailwind CSS for styling
- React Query for API state management
- React Router for navigation

### Backend
- Node.js with Express.js
- TypeScript
- PostgreSQL database
- Prisma ORM

### External APIs
- X API for user data
- xAI API for analysis

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL
- X Developer Account
- xAI API Access

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/x-dating-app.git
   cd x-dating-app
   ```

2. **Install dependencies**
   ```bash
   # Frontend
   cd client
   npm install

   # Backend
   cd ../server
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Create .env files in both client and server directories
   # See .env.example for required variables
   ```

4. **Start development servers**
   ```bash
   # Frontend (in client directory)
   npm run dev

   # Backend (in server directory)
   npm run dev
   ```

## 🏗️ Project Structure

```
x-dating-app/
├── client/                # Frontend application
│   ├── src/
│   │   ├── components/   # React components
│   │   ├── services/     # API services
│   │   ├── hooks/        # Custom hooks
│   │   ├── utils/        # Utility functions
│   │   └── styles/       # CSS/styling files
│   └── tests/
├── server/               # Backend application
│   ├── src/
│   │   ├── api/         # API routes
│   │   ├── services/    # Business logic
│   │   ├── models/      # Data models
│   │   ├── utils/       # Utility functions
│   │   └── config/      # Configuration files
│   └── tests/
└── docs/                # Documentation
```

## 📝 Environment Variables

### Frontend (.env)
```
VITE_API_URL=http://localhost:3000
VITE_X_API_KEY=your_x_api_key
```

### Backend (.env)
```
PORT=3000
DATABASE_URL=postgresql://user:password@localhost:5432/xdating
X_API_KEY=your_x_api_key
XAI_API_KEY=your_xai_api_key
JWT_SECRET=your_jwt_secret
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- @CREdebtDorian

## 🙏 Acknowledgments

- X API Documentation
- xAI API Documentation
