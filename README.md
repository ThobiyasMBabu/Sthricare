# EmpowerHer Backend

Node.js Express backend for the EmpowerHer AI Support Platform.

## Features
- JWT User Authentication
- Health Vitals Logging
- AI-powered Chat Companion (OpenAI)
- Community Posts & Interaction
- MongoDB Data Persistence

## Prerequisites
- Node.js (v18+)
- MongoDB (Local or Atlas)
- OpenAI API Key

## Getting Started

1. **Install Dependencies:**
   ```bash
   cd backend
   npm install
   ```

2. **Environment Setup:**
   - Copy `.env.example` to `.env`
   - Fill in your `MONGO_URI`, `JWT_SECRET`, and `OPENAI_API_KEY`.

3. **Run the Server:**
   ```bash
   # Development mode with nodemon
   npm run dev

   # Production mode
   npm start
   ```

## API Endpoints
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/chat/ask` - Send message to AI
- `POST /api/vitals` - Log health data
- `GET /api/community` - View community posts
