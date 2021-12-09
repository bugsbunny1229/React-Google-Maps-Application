# React Google Maps Application

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![Node.js](https://img.shields.io/badge/Node.js-v10.10.0-blue.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-v5.7.5-green.svg)](https://www.mongodb.com/)

A full-stack web application that provides an interactive Google Maps experience with marker management and location tracking capabilities.

## 🚀 Features

- 🗺️ Interactive Google Maps integration with drag-and-drop markers
- 📍 Real-time location tracking and updates
- 🎯 Custom marker placement and removal
- 📱 Responsive design for all devices
- 🔐 Secure authentication system
- 📊 Location history tracking
- 🎯 Distance calculation between markers
- 🔄 Real-time updates with WebSocket
- 📱 Mobile-friendly interface

## 🛠️ Tech Stack

### Frontend
- React.js (v16+)
- Material-UI for modern UI components
- Redux for state management
- Google Maps API integration
- React Router for client-side routing
- Axios for HTTP requests

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- CORS for cross-origin requests
- Body-parser for request handling
- Validator for input validation

## 📁 Project Structure

```
react-google-maps-app/
├── client/                 # React frontend application
│   ├── public/            # Static assets
│   │   ├── index.html     # Main HTML file
│   │   └── favicon.ico    # Application icon
│   └── src/               # React source code
│       ├── components/    # Reusable React components
│       ├── pages/         # Page components
│       ├── services/      # API services
│       ├── store/         # Redux store configuration
│       ├── utils/         # Utility functions
│       └── App.js         # Main application component
├── server/                # Node.js backend
│   ├── models/           # MongoDB models
│   ├── routes/           # API routes
│   └── server.js         # Express server configuration
├── .env                  # Environment variables
├── package.json          # Project dependencies
└── README.md            # Project documentation
```

## 🚀 Getting Started

### 📋 Prerequisites

- Node.js (v10.10.0 or higher)
- MongoDB (v4.0 or higher)
- Google Maps API Key
- npm or yarn package manager

### 🔧 Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/react-google-maps-app.git
   cd react-google-maps-app
   ```

2. Install dependencies
   ```bash
   # Install server dependencies
   npm install
   
   # Install client dependencies
   cd client
   npm install
   ```

3. Configure environment variables
   - Create a `.env` file in the root directory
   - Add the following environment variables:
   ```
   NODE_ENV=development
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/google-maps
   JWT_SECRET=your_jwt_secret_key
   GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

4. Start the development servers
   ```bash
   # Start both servers in development mode
   npm run dev
   ```

   This will start:
   - Backend server: http://localhost:5000
   - Frontend server: http://localhost:3000

### 🎯 Running the Tests

```bash
# Run tests for both frontend and backend
npm test
```

## 📱 Usage

1. Open your web browser and navigate to http://localhost:3000
2. Sign up or log in to your account
3. Use the map interface to:
   - Drag and drop markers
   - View location history
   - Calculate distances
   - Save favorite locations

## 📦 Deployment

1. Build the frontend
   ```bash
   cd client
   npm run build
   ```

2. Deploy the backend
   ```bash
   # For production
   NODE_ENV=production npm start
   ```

## 🙏 Acknowledgments

- Thanks to Google Maps API team for their excellent documentation
- Special thanks to all contributors who helped improve this project
- Inspired by various open-source mapping applications
