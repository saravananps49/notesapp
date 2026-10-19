# MERN Notes App

A full-stack Notes Management application built with the MERN stack, featuring secure authentication, role-based access control, and CRUD operations for users and notes.

## 🚀 Tech Stack

- **Frontend:** React, Redux Toolkit, RTK Query
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas, Mongoose
- **Authentication:** JWT, bcrypt
- **API:** RESTful APIs

## ✨ Features

- User login and authentication
- JWT access and refresh token handling
- Role-based access control
- Create, read, update, and delete notes
- User management with roles and active status
- Password hashing with bcrypt
- API state management using Redux Toolkit and RTK Query

## 📁 Project Structure

```text
MERN-Notes-App/
├── frontend/    # React application
└── backend/     # Express API and MongoDB integration
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd MERN-Notes-App
```

### 2. Configure the backend

Create a `.env` file inside the `backend` directory:

```env
NODE_ENV=development
DATABASE_URI=your_mongodb_connection_string
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
```

Install dependencies and start the backend:

```bash
cd backend
npm install
npm run dev
```

### 3. Configure the frontend

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

Ensure the frontend API configuration points to your running backend.

## 🔐 Security

- Passwords are hashed using bcrypt.
- JWTs are used for authentication.
- Environment variables store sensitive configuration.
- Never commit `.env` files or expose database credentials and token secrets.

## 🎯 Learning Objectives

This project demonstrates full-stack development, REST API integration, authentication, authorization, database operations, and client-side state management using the MERN ecosystem.

## 📌 Future Enhancements

- Automated testing
- Docker-based deployment
- Cloud hosting and CI/CD
- Enhanced input validation and error handling

## 👨‍💻 Author

**Saravanan PS**

