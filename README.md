# 🚀 NxtBuild — AI-Powered Web App Builder

NxtBuild is a full-stack AI application that allows users to generate complete web applications using natural language. Simply describe what you want, and the system generates a fully functional HTML/CSS/JavaScript app with a live preview.

This project demonstrates modern full-stack development with AI integration, real-time UI updates, and scalable architecture.

---

## ✨ Features

### 🔐 User Authentication
- Secure registration and login
- JWT-based authentication
- Password hashing using bcrypt

### 📁 Project Management
- Create, view, rename, and delete projects
- Persistent storage with MongoDB
- Organized dashboard for all user projects

### 🤖 AI Code Generation
- Generate complete web apps from plain English prompts
- Powered by Gemini AI
- Produces clean, runnable HTML/CSS/JS code

### 💬 Chat Interface
- Conversational UI for interacting with AI
- Iteratively refine and update generated apps
- Maintains context for better results

### 🖥️ Live Preview
- Real-time rendering of generated apps
- Embedded iframe preview
- Instant feedback loop for users

### 🧑‍💻 Code Editor
- View generated source code
- Edit and customize code directly
- Immediate preview updates

### 📥 Code Download
- Download generated app as a standalone HTML file
- Ready to use without any setup

---

## 🏗️ Tech Stack

### Frontend
- React (Vite)
- Context API (State Management)
- Vanilla CSS (Modular styling)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### AI Integration
- Gemini API (Google AI)

### Authentication
- JSON Web Tokens (JWT)
- bcrypt

---

## 📁 Project Structure
build-your-own-lovable/
│
├── client/ # React Frontend (Vite)
├── server/ # Node.js + Express Backend


---

## ⚙️ Environment Variables

### Backend (`server/.env`)
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173

### Frontend (`client/.env`)

VITE_API_URL=http://localhost:5000/api


---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/build-your-own-lovable.git

cd build-your-own-lovable


---

### 2. Setup Backend

cd server
npm install
npm run dev

---

## 🌐 Deployment

### Frontend
- Deploy on Vercel
- Set root directory to `client`

### Backend
- Deploy on Render or Railway
- Set root directory to `server`

---

## 🎯 Key Highlights

- Full-stack architecture with clear separation of concerns
- AI-driven application generation workflow
- Real-time preview + editing experience
- Production-ready structure and scalable design

---

## 📸 Screenshots (Optional)

<img width="1896" height="862" alt="Screenshot 2026-04-03 163233" src="https://github.com/user-attachments/assets/fb8ce4ba-782a-4689-9218-457918d49841" />
<img width="1903" height="863" alt="Screenshot 2026-04-03 163112" src="https://github.com/user-attachments/assets/d0538b84-cd25-4d1a-80ea-3dc6659f6f9c" />
<img width="1904" height="879" alt="Screenshot 2026-04-03 163202" src="https://github.com/user-attachments/assets/af7aa071-87c3-4128-a43c-c52978961cdc" />


---

## 📌 Future Improvements

- Multi-file code generation (React apps instead of single HTML)
- Collaboration (share projects)
- Version history for generated apps
- Better prompt optimization

---

## 👨‍💻 Author

**Addanki Adinarayana Anand Swaroop**

- Passionate Full Stack Developer
- Focused on building AI-powered applications
