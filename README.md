🚀 Scalable Web App with Authentication & Dashboard

Frontend Developer Internship Assignment

This project is a full-stack web application built as part of an internship assignment to demonstrate skills in frontend engineering, API integration, authentication, security, and scalable architecture.

The application includes a modern React frontend, a secure Node.js/Express backend, JWT-based authentication, and a dashboard with full CRUD functionality.

🔥 Features Implemented
✅ Frontend (React + Vite)

Built using React with TailwindCSS

Fully responsive UI (mobile + desktop)

Reusable components & modular structure

Authentication pages:

Register

Login

Logout

Protected Routes using JWT token

Dashboard UI:

Display logged-in user profile

CRUD operations for Notes (create, read, delete)

Real-time search & filter

Axios-based API integration with token interceptors

🛠️ Backend (Node.js + Express)

Secure authentication using:

bcrypt for password hashing

JWT for session management

Connected to MongoDB using Mongoose

REST API endpoints for:

User registration & login

Fetch/update user profile

Notes CRUD (create, get, delete)

Middlewares:

JWT authentication

Error handling

Request validation

🧱 Project Architecture
scalable-webapp/
│
├── server/            # Backend (Node.js / Express / MongoDB)
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   ├── config/
│   └── server.js
│
└── client/            # Frontend (React + Tailwind + Axios)
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── context/
    │   └── App.jsx

🔐 Security Implemented

Passwords hashed with bcrypt

JWT access tokens stored in HTTP headers

Protected backend routes

Input validation (client & server side)

Error-safe API structure

📚 Postman Collection

A complete Postman collection is included for easy API testing:

Auth APIs (Register/Login)

Profile API

Notes CRUD APIs

▶️ How to Run Locally
1️⃣ Backend
cd server
npm install
cp .env.example .env
npm start


(or nodemon server.js)

2️⃣ Frontend
cd client
npm install
cp .env.example .env
npm run dev

📈 Scalability Notes

The project is structured for long-term scaling:

Component-based UI design

Modular backend (controllers, routes, middleware separated)

Reusable service layers

Centralized API handler with Axios interceptors

Clean .env configuration for easy environment migration

Ready for Docker deployment

📝 Tech Stack

React + Vite

TailwindCSS

Node.js + Express

MongoDB + Mongoose

JWT + bcrypt

Axios

Postman
