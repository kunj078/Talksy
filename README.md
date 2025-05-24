# Talksy - The Chat Application
### Beyond Words, Weyond Distance
A real-time chat application built with a fullstack architecture using **Node.js**, **Express**, **MongoDB**, and **React**. It supports user authentication, real-time messaging, and media uploads with **Cloudinary**.

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Cloudinary (for media storage)
- JWT for authentication
- Socket.IO for real-time messaging

### Frontend
- React
- Axios
- React Router
- Tailwind CSS (or other CSS framework used)

## ✨ Features

- 🔐 User Authentication (Signup/Login)
- 👥 Manage User Profiles
- 💬 Real-time One-to-One Messaging
- 📤 Media Uploads via Cloudinary
- 🕵️ Search for Users
- 🚀 REST API Backend

## 📁 Project Structure

```
fullstack-chat-app-master/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── models/
│   │   ├── routes/
│   │   └── index.js
│   ├── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
├── .gitignore
├── README.md
└── LICENSE
```

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- MongoDB running locally or on Atlas
- Cloudinary account (for media uploads)

---

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/fullstack-chat-app.git
cd fullstack-chat-app
```

---

### 2. Backend Setup

```bash
cd backend
npm install
```

#### Environment Variables

Create a `.env` file inside the `backend/` folder with the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

#### Run Backend

```bash
npm run dev
```

---

### 3. Frontend Setup

```bash
cd ../frontend
npm install
```

#### Run Frontend

```bash
npm run dev
```

---

## 🔗 API Endpoints Overview

| Method | Endpoint            | Description             |
|--------|---------------------|-------------------------|
| POST   | /api/auth/register  | Register a new user     |
| POST   | /api/auth/login     | Login with credentials  |
| GET    | /api/users          | Get all users           |
| POST   | /api/messages       | Send a message          |
| GET    | /api/messages/:id   | Get messages for chat   |

> Check the `backend/src/routes/` folder for full route definitions.

---

## 📸 Screenshots

## Signup Page
![image](https://github.com/user-attachments/assets/0c14b57a-0ab5-43bf-acdc-44f556c6caec)

## Login Page
![image](https://github.com/user-attachments/assets/4d3caecf-9cc9-4441-91f5-ae17c64dbd04)

## Profile Page
![image](https://github.com/user-attachments/assets/8b2a4d04-6bb2-4ab0-9e7c-124b2bc3a610)

## Real Time Chat Conversation 
![image](https://github.com/user-attachments/assets/ca72d9c9-cb59-4d42-83c8-5bc9227482a8)

## Theme Setting
![image](https://github.com/user-attachments/assets/5bab22f3-baf1-4f29-bc01-02373d86385c)

##
---

## 🙌 Contributing

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Create a new Pull Request
