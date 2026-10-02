# 🚀 TaskManager (SmartFlow)

![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-4.x-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/Auth-JWT_Bearer-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

A fullstack task management platform built with the **MERN** stack (MongoDB, Express, React, Node.js). Designed with a modular **Controller-Service-Model (CSM)** backend architecture, global state management powered by **RTK Query**, and secure JWT-based stateless authentication.

---

## ✨ Key Features

- **🔐 Stateless Authentication**: Secure user registration & login using JWT (JSON Web Tokens) passed via `Authorization: Bearer <token>` headers and passwords hashed with `bcrypt`.
- **📋 Task CRUD Operations**: Full lifecycle management for tasks (creation, reading, updating status/priority, and deletion).
- **🏗️ Controller-Service-Model Architecture**: Strict separation of concerns on the backend for high scalability and maintainability.
- **⚡ Reactive State Management**: Fast, lightweight global UI state handling on the frontend using **Zustand**.
- **🛡️ Custom Middleware**: Robust CORS configuration, JWT payload verification, and centralized async error handling.
- **🎨 Responsive UI**: Modern, intuitive interface built with React and styled using Tailwind CSS.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: React.js
- **Routing**: React Router DOM
- **State Management**: RTK Query
- **Styling**: Tailwind CSS
- **HTTP Client**: Axios / Fetch API

### **Backend**
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (via Mongoose ODM)
- **Security**: JSON Web Tokens (`jsonwebtoken`), `bcryptjs`, `cors`

---
