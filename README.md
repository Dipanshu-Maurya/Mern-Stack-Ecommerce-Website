# MERN Stack E-Commerce Project

This is a full-stack MERN (MongoDB, Express, React, Node.js) e-commerce application.
The project is divided into three main parts:

- **Frontend** – User-facing React application  
- **Admin** – Admin dashboard built with React  
- **Backend** – Node.js & Express REST API

---

## Project Folder Structure

```
E-COMMERCE
│
├── Admin
├── Backend
└── Frontend
```

---

## Prerequisites

Make sure you have the following installed:

- Node.js (v16 or above)
- npm or yarn
- MongoDB (local or Atlas)

---

## 1. Clone the Repository

```bash
git clone https://github.com/Dipanshu-Maurya/Mern-Stack-Ecommerce-Website.git
cd E-COMMERCE
```

---

## 2. Backend Setup

```bash
cd Backend
npm install
npm start
```

Backend will run on:
```
http://localhost:4000
```

---

## 3. Frontend Setup

```bash
cd Frontend
npm install
npm start
```

Frontend will run on:
```
http://localhost:5173
```

---

## 4. Admin Panel Setup

```bash
cd Admin
npm install
npm start
```

Admin panel will run on:
```
http://localhost:5174
```

---

## Environment Variables

Create a `.env` file inside the **Backend** folder and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=4000
```

---

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- JWT Authentication
- Multer
- CORS

---

## Note

- `node_modules` are ignored using `.gitignore`
- Install dependencies separately for **Backend**, **Frontend**, and **Admin**

---


This project is licensed under the ISC License.

