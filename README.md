# Resume Builder

A full-stack Resume Builder web application customized exactly to your needs. This project allows seamless creation, viewing, and exporting of resumes online.

## Core Stack
- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB (Atlas)
- **AI Integration**: Gemini API (for smart resume generation)
- **Image Storage**: ImageKit

## How to Run Locally

### 1. Backend (Server)
Open a terminal in the project root and navigate to the `server` directory:
```bash
cd server
npm install
npm run server
```

The database keys are fully configured, and it will run on `http://localhost:3000`.

### 2. Frontend (Client)
Open another terminal in the project root and navigate to the `client` directory:
```bash
cd client
npm install
npm run dev
```

The React frontend will serve on `http://localhost:5173`. Open this URL in your browser to begin testing out the Resume Builder.

## Production
Ready to deploy this exact code directly through platforms like Vercel or render. The environment files `.env` are safely documented in `.gitignore`.
