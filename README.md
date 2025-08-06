# 💬 Real-Time Chat App

A full-stack real-time chat application with support for **text messaging**, **image sharing (Cloudinary)**, **user authentication**, and **live message updates** using **Socket.IO**. Built with:

- 🔧 **Node.js**, **Express**, **MongoDB**
- ⚛️ **React + Vite**, **Tailwind CSS**
- 🔒 **JWT Auth**
- ☁️ **Cloudinary**
- 🔌 **Socket.IO**

---

## 📁 Project Structure

### Backend (Node.js + Express + MongoDB)
backend/
├── src/
│ ├── controllers/
│ ├── lib/
│ ├── middleware/
│ ├── models/
│ │ ├── message.model.js
│ │ └── user.model.js
│ ├── routes/
│ │ └── index.js
│ └── index.js
├── .env
├── package.json



### Frontend (React + Vite)

frontend/
├── src/
│ ├── components/
│ ├── constants/
│ ├── lib/
│ ├── pages/
│ │ ├── HomePage.jsx
│ │ ├── LoginPage.jsx
│ │ ├── ProfilePage.jsx
│ │ ├── SettingsPage.jsx
│ │ └── SignUpPage.jsx
│ ├── store/
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
├── tailwind.config.js
├── vite.config.js



---

## 🚀 Features

- 🔐 **JWT Authentication** (Signup/Login)
- 🗨️ **Real-Time Messaging** using Socket.IO
- 🖼️ **Image Uploads** via Cloudinary
- 💻 Fully responsive UI with TailwindCSS
- 👤 Profile and Settings Page
- 💬 Live typing indicator (optional)
- 📦 Clean and modular folder structure

---

## ⚙️ Installation

### 1️⃣ Backend Setup

```bash
cd backend
npm install
```
Create a .env file in backend/ with:
```bash
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
````

Start the backend:
```bash
npm run dev
````

2️⃣ Frontend Setup
```bash
cd frontend
npm install
````
Start the frontend:
```bash
npm run dev
```

🔌 Technologies Used

| Tech         | Usage                             |
| ------------ | --------------------------------- |
| React + Vite | Frontend framework                |
| Tailwind CSS | Styling                           |
| Node.js      | Backend runtime                   |
| Express      | Backend framework                 |
| MongoDB      | Database                          |
| Mongoose     | MongoDB ODM                       |
| Socket.IO    | Real-time WebSocket communication |
| Cloudinary   | Image storage & delivery          |
| JWT          | Auth token management             |

✅ Todos

☑️ User authentication (JWT)

☑️ Socket.IO integration

☑️Image upload via Cloudinary

☑️Chat UI
