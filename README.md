# 🚀 ChatApp

A full-stack real-time chat application using **React**, **Zustand**, **Socket.io**, **Node.js**, **Express**, and **MongoDB**.

---

## ⭐ Features
- 🔐 User Authentication (JWT + Cookies)
- 💬 Real-time Messaging (Socket.io)
- 🎨 30+ Themes (DaisyUI)
- 👤 Profile Update
- 🌙 Dark/Light Mode
- 📱 Responsive UI

---

## 🧰 Tech Stack
**Frontend:** React, Vite, TailwindCSS, DaisyUI, Zustand, Axios  
**Backend:** Node.js, Express, MongoDB, Socket.io  
**Auth:** JWT + httpOnly Cookies  

---

## ⚙️ Environment Variables

### Backend `.env`
```
PORT=5001
MONGO_URI=your-mongo-uri
JWT_SECRET=your-secret
```

### Frontend `.env`
```
VITE_API_URL=https://your-backend-url.com
```

---

## ▶️ Run Locally

### Backend
```
cd backend
npm install
npm run dev
```

### Frontend
```
cd frontend
npm install
npm run dev
```

---

## 🌐 API Endpoints
```
POST   /api/auth/signup
POST   /api/auth/login
POST   /api/auth/logout
GET    /api/auth/check
PUT    /api/auth/update-profile

GET    /api/messages/:userId
POST   /api/messages/send/:userId
```

---

## 🗂️ Folder Structure
```
backend/
frontend/
README.md
```

---

## 📦 Deployment
- Frontend → Vercel / Cloudflare Pages  
- Backend → Render / Railway  

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub.
