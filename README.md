# 🚀 AI Job Preparation Platform

> **An intelligent, full-stack job preparation web application powered by Google Gemini AI — helping candidates ace interviews and optimize resumes with the power of artificial intelligence.**

![Tech Stack](https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

---

## 🧠 About the Project

**AI Job Preparation Platform** is a production-ready, full-stack web application designed to help job seekers prepare smarter and faster. By integrating **Google Gemini AI**, the platform provides:

- AI-generated, role-specific interview questions
- Intelligent resume analysis and feedback
- Secure user accounts with JWT authentication
- Clean, responsive UI for a seamless experience

Whether you're a fresher or an experienced professional, this platform gives you the edge you need in today's competitive job market.

---

## ✨ Features

- 🤖 **AI-Powered Interview Questions** — Generate role-specific questions instantly using Gemini AI
- 📄 **Resume Analysis** — Get intelligent feedback on your resume with AI-driven suggestions
- 🔐 **Secure Authentication** — JWT-based login/signup with protected routes
- 📱 **Fully Responsive UI** — Works seamlessly on mobile, tablet, and desktop
- ⚡ **RESTful API Architecture** — Clean, scalable backend API design
- 💾 **Persistent Data Storage** — MongoDB stores user data, sessions, and history securely
- 🎯 **Role-Based Preparation** — Customize prep based on job role and experience level

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| React.js | UI component library |
| Tailwind CSS | Styling & responsive design |
| React Router | Client-side routing |
| Axios / Fetch | API communication |
| React Hooks | State & lifecycle management |

### Backend
| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| Express.js | Web framework & REST API |
| MongoDB | NoSQL database |
| Mongoose | ODM for MongoDB |
| JWT | Authentication & authorization |
| Google Gemini API | AI-powered features |

### Tools & DevOps
| Tool | Purpose |
|---|---|
| Git & GitHub | Version control |
| Postman | API testing |
| VS Code | Code editor |
| MongoDB Compass | Database GUI |
| DevTools | Debugging |

---

## 📁 Project Structure

```
ai-job-prep/
│
├── frontend/                  # React.js frontend
│   ├── public/
│   └── src/
│       ├── components/        # Reusable UI components
│       ├── pages/             # Route-level pages
│       ├── hooks/             # Custom React hooks
│       ├── services/          # API call functions (Axios)
│       └── App.jsx
│
├── backend/                   # Node.js + Express backend
│   ├── controllers/           # Route handler logic
│   ├── models/                # Mongoose schemas
│   ├── routes/                # API route definitions
│   ├── middleware/            # Auth & error middleware
│   ├── config/                # DB & env config
│   └── server.js
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v18+)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Git](https://git-scm.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-job-prep.git
cd ai-job-prep
```

### 2. Setup Backend

```bash
cd backend
npm install
npm run dev
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file in the `/backend` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GEMINI_API_KEY=your_google_gemini_api_key
```

> ⚠️ Never push your `.env` file to GitHub. Add it to `.gitignore`.

---

## 📡 API Endpoints

### Auth Routes
| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | Login & get JWT token |

### AI Routes
| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/ai/generate-questions` | Generate interview questions |
| POST | `/api/ai/analyze-resume` | Analyze resume with AI |

### User Routes
| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/user/profile` | Get user profile |
| PUT | `/api/user/update` | Update user profile |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Aditya Chauhan**
- GitHub: [@Aditya-Chauhan-Dev](https://github.com/Aditya-Chauhan-Dev)


---

> ⭐ **If you found this project helpful, please give it a star!** It motivates me to build more awesome projects.
