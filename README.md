# 🎟️ Eventora – Full Stack Event Management Platform

🚀 **Live Demo:** https://eventora-gilt.vercel.app/

---

## 📌 Overview

Eventora is a full-stack event management platform that allows users to **browse, search, and explore events seamlessly**. It provides a modern UI with efficient backend integration for handling event data dynamically.

This project demonstrates strong skills in **full-stack development, API integration, and deployment**.

---

## ✨ Features

* 🔍 Search events by keyword
* 📅 View detailed event information
* 📍 Location and time display
* ⚡ Fast and responsive UI
* 🌐 Deployed frontend and backend
* 🔐 Secure API handling

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Deployment

* Frontend: Vercel
* Backend: Vercel / (Recommended: Render)

---

## 📂 Project Structure

```
Eventora/
│
├── client/        # Frontend (React)
├── server/        # Backend (Node + Express)
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Eventora.git
cd Eventora
```

---

### 2️⃣ Setup Backend

```bash
cd server
npm install
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
EMAIL_USER = your_email_id_for_mail
EMAIL_PASS = your_pass_email_access
PORT=5000
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Setup Frontend

```bash
cd client
npm install
npm start
```

---

## 🌍 API Endpoints

| Method | Endpoint       | Description      |
| ------ | -------------- | ---------------- |
| GET    | /api/events    | Fetch all events |
| GET    | /api/events?q= | Search events    |

---

## 🚀 Future Enhancements

* ❤️ Wishlist / Bookmarks
  
---

## 👨‍💻 Author

**Saksham Singla**
DTU B.Tech CSE | Aspiring Software Engineer

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!
