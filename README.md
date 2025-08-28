# Streamify - Real-Time Video Chat & Social App

![Streamify](https://img.shields.io/badge/Streamify-MERN_Stack_App-blue) ![Version](https://img.shields.io/badge/version-1.0.0-green) ![License](https://img.shields.io/badge/license-MIT-yellow)

A full-stack real-time video calling and chat application built with the MERN stack, featuring social networking capabilities, 32 UI themes, and seamless user experience.

## 🚀 Live Demo

[Coming Soon...](#)

## ✨ Key Features

- 🚀 **Modern Tech Stack**: Node.js, Express, MongoDB, React, TanStack Query, Tailwind CSS
- 🔐 **Secure Authentication**: JWT-based login & signup flows
- 📄 **Onboarding Flow**: Smooth user onboarding experience
- 👥 **Friends System**: Add, accept, and manage friends
- 💬 **Real-Time Chat**: Instant messaging with WebSocket integration
- 📹 **Video Calling**: High-quality video calls with WebRTC
- 🎨 **32 UI Themes**: Extensive customization options
- 🚨 **Protected Routes**: Secure navigation with authentication guards
- 🛠 **Custom Hooks**: Reusable React hooks following best practices
- 🧪 **API Testing**: Comprehensive endpoint testing for reliability
- 🚀 **Deployment Ready**: Optimized for production deployment

## 🛠 Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **JWT** - Authentication
- **Socket.IO** - Real-time communication
- **WebRTC** - Video calling

### Frontend
- **React** - UI library
- **TanStack Query** - Server state management
- **Tailwind CSS** - Styling framework
- **Axios** - HTTP client
- **React Router** - Navigation

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Backend Setup
1. Navigate to the backend directory:
```bash
cd backend

2. Install dependencies:
npm install

3. Create a .env file in the backend root with:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STREAM_API_KEY=your_getstream_api_key
STREAM_API_SECRET=your_getstream_api_secret

4. Start the development server:
npm run dev

### Frontend Setup
1. Navigate to the frontend directory:
cd frontend

2. Install dependencies:
npm install

3. Create a .env file in the frontend root with:
VITE_API_BASE_URL=http://localhost:5000/api

4. Start the development server:
npm run dev

## 📁 Project Structure

Streamify/
├── backend/
│   ├── src/
│   │   ├── controllers/    # Route controllers
│   │   ├── lib/           # Utility libraries
│   │   ├── middleware/    # Custom middleware
│   │   ├── models/        # Database models
│   │   ├── routes/        # API routes
│   │   └── server.js      # Server entry point
│   ├── .env              # Environment variables
│   └── package.json
└── frontend/
    ├── src/
    │   ├── components/    # Reusable components
    │   ├── constants/     # App constants
    │   ├── hooks/         # Custom React hooks
    │   ├── lib/           # Utility libraries
    │   ├── pages/         # Page components
    │   ├── store/         # State management
    │   ├── App.jsx        # Main App component
    │   └── main.jsx       # React entry point
    ├── .env              # Environment variables
    └── package.json

## 🔌 API Endpoints

### Authentication
- POST /api/auth/signup - User registration
- POST /api/auth/login - User login
- POST /api/auth/logout - User logout

### User Management
- POST /api/users/onboarding - Complete user onboarding
- GET /api/users/recommended - Get recommended users
- GET /api/users/friends - Get user's friends

### Friend System
- POST /api/friends/request - Send friend request
- POST /api/friends/accept - Accept friend request

### Chat
- GET /api/chat/conversations - Get user conversations
- GET /api/chat/messages/:conversationId - Get conversation messages
- POST /api/chat/message - Send a message

## 🎨 UI Themes

Streamify comes with 32 beautifully crafted themes. Users can switch between themes seamlessly, with preferences saved to their account.

## 🤝 Contributing
We welcome contributions to Streamify! Please feel free to submit pull requests, create issues, or suggest new features.

1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 🙏 Acknowledgments

- Icons from [Heroicons](https://heroicons.com/)
- UI inspiration from various modern applications
- The MERN community for excellent documentation and resources

## 📞 Support

If you have any questions or need help with setup, please open an issue or contact us at [email protected]
```
