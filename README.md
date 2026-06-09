# Personal Portfolio

A complete full-stack Personal Portfolio built with the MERN stack.

## Features
- Fully responsive modern design (Tailwind CSS)
- Dark/Light mode toggle
- Beautiful animations using Framer Motion
- Admin Dashboard for CMS (Projects, Certifications, Contact Messages)
- JWT Authentication

## Prerequisites
- Node.js
- MongoDB (Local or Atlas)

## Getting Started

### 1. Clone the repository
\`\`\`bash
git clone <repository-url>
cd <repository-directory>
\`\`\`

### 2. Backend Setup
\`\`\`bash
cd backend
npm install
\`\`\`
- Rename `.env.example` to `.env` and fill in your details (MongoDB URI, JWT Secret).
- Start the server:
\`\`\`bash
npm run dev
\`\`\`

### 3. Frontend Setup
\`\`\`bash
cd frontend
npm install
\`\`\`
- Ensure backend is running, then start the frontend:
\`\`\`bash
npm run dev
\`\`\`

## Initializing Admin User
To initialize the first admin user, send a POST request to `http://localhost:5000/api/auth/register` with `email` and `password` in the body. Once created, you can log in at `/admin/login`.

## Deployment
- **Frontend**: Recommend deploying on Vercel or Netlify. Build command: `npm run build`.
- **Backend**: Recommend deploying on Render or Heroku.
- **Database**: MongoDB Atlas.
