# MERN Chat App

## Overview
This project is a real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js). It provides users with a seamless and interactive chatting experience, leveraging modern web technologies and libraries.

## Frontend Technologies
- **React**: A powerful JavaScript library for building user interfaces.
- **React DOM**: Serves as the entry point to the DOM and server renderers for React.
- **React Hot Toast**: Provides a simple and customizable notification system.
- **React Icons**: A collection of popular icons for React projects.
- **React Router DOM**: Handles routing and navigation within the application.
- **Socket.IO Client**: Enables real-time, bidirectional communication between web clients and servers.
- **Zustand**: A small, fast, and scalable state-management solution for React.

## Backend Technologies
- **Express**: A minimal and flexible Node.js web application framework.
- **Mongoose**: An elegant MongoDB object modeling tool for Node.js.
- **Socket.IO**: Enables real-time, bidirectional communication between web clients and servers.
- **Bcryptjs**: A library to hash passwords, ensuring secure user authentication.
- **Cookie-Parser**: Parses cookie header and populates req.cookies with an object keyed by the cookie names.
- **Dotenv**: Loads environment variables from a .env file into process.env.
- **Jsonwebtoken**: A library to create and verify JSON Web Tokens, providing a secure authentication mechanism.

## Key Features
- **Real-Time Communication**: Utilizes Socket.IO for instant messaging capabilities.
- **User Authentication**: Secure login and registration system with hashed passwords using Bcryptjs.
- **Persistent Storage**: Stores user data and chat history in MongoDB, managed with Mongoose.
- **Responsive UI**: A user-friendly and responsive interface built with React.
- **State Management**: Efficient state management using Zustand.
- **Notifications**: Real-time notifications using React Hot Toast.
- **Routing**: Smooth navigation and routing with React Router DOM.

## Installation
1. Clone the repository.
2. Navigate to the frontend and backend directories and install the dependencies:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
