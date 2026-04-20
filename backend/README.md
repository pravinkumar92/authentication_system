# Backend

Express API with JWT auth.

## Setup

```bash
npm install
```

Create `.env`:
```
MONGODB_URI=mongodb://localhost:27017/auth-system
JWT_SECRET=your_secret_key
PORT=5000
```

## Run

```bash
npm start
```

## Files

- `server.js` - Main server
- `models.js` - User schema
- `controllers.js` - Auth logic
- `auth.js` - JWT middleware
