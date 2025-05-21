# 💬 Chatty App

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://chatty-app-7590.onrender.com/)
![GitHub last commit](https://img.shields.io/github/last-commit/JayaramSunkara/Chatty-App)

A real-time chat application built with modern web technologies. Connect and chat with friends instantly!

## Highlights

- **Tech Stack**: MERN (MongoDB, Express.js, React, Node.js) + Socket.io + TailwindCSS + Daisy UI  
- **Authentication & Authorization**: Secure user login and access control with JWT  
- **Real-Time Messaging**: Instant chat functionality powered by Socket.io  
- **Online User Status**: See who's online in real-time  
- **Global State Management**: Efficient state handling with Zustand  
- **Error Handling**: Robust error management on both client and server sides  
- **Free Deployment**: Deploy like a pro with platforms like Vercel or Render!  
- **And Much More**: Explore additional features like message persistence, responsive design, and more!


## Prerequisites

Before setting up the project, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)
- [Cloudinary](https://cloudinary.com/) account for media uploads (optional, if used)
- [Git](https://git-scm.com/) for cloning the repository

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/JayaramSunkara/Chatty-App.git
   cd Chatty-App
   ```
2. **Setup Environment Variables**
   Create a `.env` file in the `root` directory and add the following:
   ```env
   
   MONGODB_URI=your_mongodb_connection_string
   
   PORT=5001
   
   JWT_SECRET=your_jwt_secret_key
   
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   
   NODE_ENV=development
   ```
3. **Build the app**
   ```bash
   npm run build
   ```
4. **Start the app**
   ```bash
   npm start
   ```
5. **Access the app** Open your browser and navigate to http://localhost:5001 (or the port specified in your .env file).

