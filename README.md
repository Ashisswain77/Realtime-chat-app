# 💬 MERN Real-Time Chat Application

A **full-stack real-time chat application** built with the **MERN** stack (MongoDB, Express, React, Node.js) and **Socket.io** for instant messaging.  
Includes **JWT-based authentication**, **Zustand** for global state management, Cloudinary for media uploads, and production-ready deployment steps.

---

## Overview
This repository provides a professional-grade, production-minded real-time chat application. It focuses on reliability, security, and developer ergonomics:
- Persistent chats stored in MongoDB
- Real-time messaging via Socket.io
- Secure auth with JWTs
- Lightweight global state with Zustand
- Cloudinary-based media handling for images/files
- Robust error handling on both server and client sides
- Deployment notes for services like Render / Railway (backend) and Vercel / Netlify (frontend)

---

## Features
- User registration and login with hashed passwords
- JWT-based session authentication and route protection
- Private and group chats (room-based)
- Real-time message delivery and presence indicators (online/offline)
- Message persistence (MongoDB)
- Image/file uploads via Cloudinary
- Typing indicators and read receipts (optional)
- Responsive UI (mobile-first)
- Centralized client state management (Zustand)
- Centralized error handling with structured responses

---

## Tech Stack

**Frontend**
- React (Vite or Create React App)
- Zustand (global state)
- Axios (HTTP requests)
- Socket.io-client (real-time)
- React Router
- Cloudinary upload widget or direct signed upload support

**Backend**
- Node.js + Express
- MongoDB + Mongoose
- Socket.io (server)
- bcryptjs (password hashing)
- jsonwebtoken (JWT)
- multer/cloudinary SDK (uploads)
- dotenv, cors, helmet (security & env)
- winston or pino (logging)

**Dev Tools**
- nodemon (auto-reload)
- eslint / prettier
- GitHub Actions (optional CI)

---

## Architecture (high-level)

npm run build
```

### Start the app

```shell
npm start
```


