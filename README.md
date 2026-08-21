# 🤖 AI Mock Interview Platform

An AI-powered mock interview platform designed to help candidates practice technical interviews in a realistic and interactive environment.

The platform allows users to select an interview role and difficulty level, participate in AI-generated mock interviews, answer questions using text or voice, and receive feedback and scores after the interview.

## 🚀 Live Demo

### Frontend
Coming Soon

### Backend API
https://ai-mock-interview-platform-oxjo.onrender.com

## ✨ Features

- 🔐 User Registration and Login
- 🔑 JWT-based Authentication
- 🎯 Role-based Mock Interviews
- 📊 Multiple Interview Difficulty Levels
- 🤖 AI-generated Interview Questions
- 💬 Interactive Interview Experience
- 🎤 Voice-based Interview Support
- 🔊 AI Voice Generation
- 📝 Resume Upload and Analysis
- 📈 Interview Score and Feedback
- 📚 Interview History
- 💻 Coding Questions with Code Editor
- 📱 Responsive User Interface

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- Axios
- React Router

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer

### AI Services

- Google Gemini API
- Murf AI
- AssemblyAI

### Deployment

- Vercel - Frontend
- Render - Backend
- MongoDB Atlas - Database

## 📂 Project Structure

AI-Mock-Interview_Platform/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── constants/
│   │   ├── context/
│   │   ├── pages/
│   │   └── services/
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
│
├── server/
│   ├── src/
│   │   ├── config/
│   │   ├── constants/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── utils/
│   ├── server.js
│   └── package.json
│
├── .gitignore
└── README.md

## ⚙️ Installation

### 1. Clone the Repository

git clone https://github.com/AbhinavRaskar/AI-Mock-Interview_Platform.git

### 2. Navigate to the Project

cd AI-Mock-Interview_Platform

## 🎨 Frontend Setup

Navigate to the client folder:

cd client

Install dependencies:

npm install

Create a `.env` file inside the `client` folder:

VITE_API_URL=http://localhost:5000/api

Start the development server:

npm run dev

Frontend will run at:

http://localhost:5173

## 🖥️ Backend Setup

Open another terminal and navigate to the server:

cd server

Install dependencies:

npm install

Create a `.env` file inside the `server` folder:

PORT=5000
NODE_ENV=development

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d

GEMINI_API_KEY=your_gemini_api_key
MURF_API_KEY=your_murf_api_key
ASSEMBLYAI_API_KEY=your_assemblyai_api_key

CLIENT_URL=http://localhost:5173

Start the backend:

npm run dev

Backend will run at:

http://localhost:5000

## 🔐 Environment Variables

For security, never commit `.env` files or API keys to GitHub.

### Backend Environment Variables

| Variable | Description |
|---|---|
| `MONGODB_URI` | MongoDB Atlas connection string |
| `JWT_SECRET` | Secret key used for JWT authentication |
| `JWT_EXPIRES_IN` | JWT token expiration duration |
| `GEMINI_API_KEY` | Google Gemini API key |
| `MURF_API_KEY` | Murf AI API key |
| `ASSEMBLYAI_API_KEY` | AssemblyAI API key |
| `CLIENT_URL` | Frontend application URL |

### Frontend Environment Variable

| Variable | Description |
|---|---|
| `VITE_API_URL` | Backend API URL |

## 🌐 Production Deployment

### Backend

The backend is deployed on Render.

Backend URL:

https://ai-mock-interview-platform-oxjo.onrender.com

### Frontend

The frontend is deployed using Vercel.

For production, configure:

VITE_API_URL=https://ai-mock-interview-platform-oxjo.onrender.com/api

## 🏗️ Application Architecture

                    ┌─────────────────┐
                    │      User       │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │ React Frontend  │
                    │     Vercel      │
                    └────────┬────────┘
                             │
                         REST API
                             │
                             ▼
                    ┌─────────────────┐
                    │ Node + Express  │
                    │     Render      │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
              ▼              ▼              ▼
         MongoDB Atlas   Gemini API    AI Services
                                         │
                                  ┌──────┴──────┐
                                  │             │
                                Murf       AssemblyAI

## 📊 Main Modules

### Authentication

- User registration
- User login
- JWT authentication
- Protected routes

### Mock Interviews

- Interview role selection
- Difficulty selection
- AI-generated questions
- Interactive interview sessions
- Interview scoring

### Voice Interview

- Voice recording
- Speech-to-text processing
- AI-generated responses
- Text-to-speech generation

### Resume

- Resume upload
- Resume processing
- AI-based resume analysis

### History

- Previous interview records
- Scores
- Feedback
- Interview performance tracking

## 🔮 Future Improvements

- 📊 Advanced performance analytics
- 🎯 Personalized interview recommendations
- 📄 Resume-based interview questions
- 🧠 Adaptive interview difficulty
- 📧 Email-based interview reports
- 📈 Detailed candidate performance dashboard
- 🎥 Video interview support
- 🏆 Interview progress and achievement system

## 👨‍💻 Author

### Abhinav Raskar

Computer Engineering | Full Stack Developer

GitHub:
https://github.com/AbhinavRaskar

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ star.

---

Built with React, Node.js, Express, MongoDB and AI technologies.
