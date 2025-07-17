# MERN Blog Application 📝

A full-featured blog application built using the **MERN** stack (MongoDB, Express, React, Node.js). This app allows users to register, log in, create posts, view articles, comment, and filter posts by categories.

---

## 🌟 Features

- 🔐 User Authentication (JWT-based)
- 📝 Create, Read, Update, Delete (CRUD) for Blog Posts
- 🗂️ Category filtering with dropdown
- 💬 Commenting system
- 📷 Image upload with preview
- 🔍 Search functionality
- ⚙️ Admin features (optional)
- 📱 Responsive UI with Tailwind CSS

---

## 🚀 Tech Stack

**Frontend:**
- React (Vite)
- Tailwind CSS
- Axios
- React Router
- React Toastify

**Backend:**
- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose
- Multer (for image uploads)
- JSON Web Token (JWT)

---

## 📁 Folder Structure

mern-blog/
│
├── client/ # React Frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ ├── hooks/
│ │ ├── services/
│ │ └── App.jsx
│ └── index.html
│
├── server/ # Node.js Backend
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── middleware/
│ └── server.js
│
├── .env
├── README.md
└── package.json


---

## ⚙️ Setup Instructions

### 🔧 Prerequisites
- Node.js
- pnpm or npm
- MongoDB (Atlas or Local)

---

### 🖥️ Backend Setup

```bash
cd server
pnpm install
Create a .env file in the server/ directory:


PORT=5000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/mernblog
JWT_SECRET=yourSecretKey
Run the server:


pnpm run dev
🌐 Frontend Setup

cd client
pnpm install
Create a .env file in the client/ directory:

VITE_API_URL=http://localhost:5000/api
Start the development server:


pnpm run dev
