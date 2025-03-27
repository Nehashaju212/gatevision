# gatevision

gate-vision/
├── client/                     # Frontend code
│   ├── public/                 # Static files
│   └── src/
│       ├── components/         # React components
│       │   ├── auth/           # Authentication components
│       │   ├── dashboard/      # Dashboard components
│       │   ├── exams/          # Exam-related components
│       │   └── results/        # Result components
│       ├── pages/              # Page components
│       ├── services/           # API services
│       └── utils/              # Utility functions
├── server/                     # Backend code
│   ├── controllers/            # Route controllers
│   ├── models/                 # Database models
│   ├── routes/                 # API routes
│   ├── middleware/             # Custom middleware
│   ├── config/                 # Configuration files
│   └── utils/                  # Utility functions
├── database/                   # Database scripts
│   ├── migrations/             # Database migrations
│   └── seeds/                  # Seed data
└── docs/                       # Documentation

# Gate Vision - Online Examination Platform

## Project Overview
Gate Vision is a comprehensive web-based online examination platform designed for educational institutions, supporting multiple engineering departments and subjects.

## Features
- User Authentication (Teacher/Student)
- Google OAuth Login
- Department and Subject-based Exams
- Real-time Exam Interface
- Instant Result Tracking

## Prerequisites
- Node.js (v18+)
- MongoDB
- npm or yarn

## Frontend Setup
1. Clone the repository
2. Navigate to the client directory
3. Install dependencies
```bash
cd client
npm install
```

## Backend Setup
1. Navigate to the server directory
2. Install dependencies
```bash
cd server
npm install
```

## Environment Variables
Create `.env` files in both client and server directories with:
- `MONGO_URI`
- `JWT_SECRET`
- `GOOGLE_CLIENT_ID`
- `GOOGLE_CLIENT_SECRET`

## Running the Application
1. Start MongoDB
2. Run backend server
```bash
cd server
npm run dev
```
3. Run frontend application
```bash
cd client
npm start
```

## Deployment
- Frontend: Vercel, Netlify
- Backend: Heroku, DigitalOcean
- Database: MongoDB Atlas
