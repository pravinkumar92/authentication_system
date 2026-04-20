# Authentication System

Full-stack authentication app with MERN stack.

## Features

- User signup and login
- JWT authentication
- Protected dashboard
- Password hashing with bcrypt

## Tech Stack

**Frontend:** React, React Router, Axios  
**Backend:** Node.js, Express, MongoDB, JWT

## Setup

### Backend

```bash
cd backend
npm install
```

Create `.env` file:
```
MONGODB_URI=mongodb://localhost:27017/auth-system
JWT_SECRET=your_secret_key
PORT=5000
FRONTEND_URL=http://localhost:3000
```

### Frontend

```bash
cd frontend
npm install
```

## Run

Backend:
```bash
cd backend
npm start
```

Frontend (new terminal):
```bash
cd frontend
npm start
```

Open http://localhost:3000

## API

```
POST /api/auth/signup    - Register
POST /api/auth/login     - Login
GET  /api/dashboard      - Dashboard (protected)
```

## Structure

```
backend/
├── auth.js          # JWT middleware
├── controllers.js   # Route handlers
├── models.js        # User model
└── server.js        # Main file

frontend/src/
├── components/      # All components
└── App.js
```
