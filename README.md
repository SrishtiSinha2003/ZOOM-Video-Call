# Zoom Video Call Application

A comprehensive, feature-rich video call application developed using **React**, **JavaScript**, and **MongoDB**. This project provides a seamless experience for users to conduct video and audio calls with options to sign up, sign in, or join as a guest. Equipped with screen sharing, call history, and a fully secure authentication system, this application is designed to offer high-quality video conferencing similar to popular platforms like Zoom.

The real-time communication is powered by **WebRTC**, while **Socket.io** handles the underlying messaging infrastructure for instant and efficient data transfer between clients and servers. For security, the app implements **bcrypt** for password hashing and **crypto** for encryption, ensuring user data protection.

## Features

- **User Authentication**: Sign up and sign in with hashed passwords using bcrypt, or join as a guest.
- **Video/Audio Calls**: High-quality video and audio calls using WebRTC.
- **Screen Sharing**: Share your screen with other participants during the call.The screen share 
                      is updated in real time for all participants in the room, ensuring a 
                       smooth and synchronized experience.
- **Call History**: View previous call records for registered users.Guests are provided with the 
                     same video and audio features but without access to history or other 
                    personalized features.
- **Join as Guest**: Start or join calls without needing an account.
- **Real-time Communication**: Instant audio, video, and chat messaging using Socket.io.
- **Responsive UI**: Built with Material UI for a modern and responsive user interface.

## Tech Stack
# Frontend
- React: The frontend is built with React, a popular JavaScript library for building dynamic and responsive user interfaces. React enables smooth transitions between different views and efficient component-based development.
- JavaScript: Vanilla JavaScript is used alongside React for DOM manipulation, handling asynchronous operations, and managing application state.
- Material UI: Provides the pre-built, customizable UI components used throughout the application to maintain a consistent and responsive design.
- CSS: Custom CSS styles are applied to handle specific design aspects, with a focus on making the interface user-friendly and responsive on both desktop and mobile devices.

 # Backend
- Node.js: Node.js serves as the runtime environment for building the server-side application. It enables the creation of scalable and fast backend APIs to handle requests from the client.
- Express.js: Express is the framework used for building the backend server, providing routes and middleware for efficient request/response handling.
- Socket.io: Used for real-time communication between clients, enabling instant data transfer for features like messaging and call notifications.
- WebRTC: Powers the peer-to-peer video/audio communication capabilities. WebRTC is an open-source project that provides APIs to allow real-time media exchange directly between browsers.
- Axios: Axios is used to handle HTTP requests between the frontend and backend. It simplifies API calls to the server for tasks like fetching user data, creating new rooms, and updating the call history.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/zoom-video-call.git
   cd zoom-video-call

   
2. Install server dependencies
   ```bash
   cd frontend
   npm start

## Dependencies
# Backend:
Node.js
Express.js
Socket.io
MongoDB
bcrypt
crypto
# Frontend:
React
Material UI
WebRTC
Axios   
