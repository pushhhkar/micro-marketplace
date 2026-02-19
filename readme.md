# 🛒 Micro Marketplace App

A full-stack **Micro Marketplace Application** built using **Node.js, React, and React Native**.

This project demonstrates a complete marketplace workflow including authentication, product browsing, search, pagination, favorites management, and mobile support.

---

## 🚀 Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* bcrypt Password Hashing

### Web Application

* React (Vite)
* Axios
* Responsive CSS UI

### Mobile Application

* React Native (Expo Router)
* AsyncStorage (JWT persistence)

---

## ✨ Features

### Authentication

* User Register & Login
* JWT Secure APIs
* Password Hashing

### Products

* Product Listing
* Search Functionality
* Pagination Support
* Product Detail Page

### Favorites

* Add Favorite ❤️
* Remove Favorite ❤️
* Protected Routes

### Web UI

* Responsive Product Cards
* Search Bar
* Pagination Controls
* Modern Navbar

### Mobile App

* Login Authentication
* Product Browsing
* Product Detail Screen
* Favorite Management

---

## 📂 Project Structure

```
micro-marketplace
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── seed
│   └── utils
│
├── web
│   ├── components
│   ├── pages
│   └── services
│
└── mobile
    ├── app
    ├── assets
    └── services
```

---

## ⚙️ Setup Instructions

---

### 1️⃣ Backend Setup

```
cd backend
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

Run Backend:

```
npm run dev
```

Seed Database:

```
npm run seed
```

---

### 2️⃣ Web Application Setup

```
cd web
npm install
npm run dev
```

Open in browser:

```
http://localhost:5173
```

---

### 3️⃣ Mobile Application Setup

```
cd mobile
npm install
npm start
```

Scan QR using **Expo Go App** on your mobile phone.

⚠️ Update API base URL inside:

```
mobile/app/services/api.js
```

Replace localhost with your local IP address:

Example:

```
http://192.168.1.5:5000
```

---

## 🔐 Test Credentials

Use seeded users:

```
Email: user1@mail.com
Password: 123456
```

---

## 📡 API Endpoints

### Authentication

```
POST /auth/register
POST /auth/login
```

---

### Products

```
GET /products
GET /products/:id
```

Supports:

* Search
* Pagination

---

### Favorites

```
GET /favorites
POST /favorites/:id
DELETE /favorites/:id
```

---

## 🎥 Demo

Demo video or deployed links can be added here.

Example:

```
Demo Video: <add link>
Web Deployment: <add link>
```

---

## ✅ Evaluation Criteria Covered

* Authentication ✔
* REST API Structure ✔
* Code Organization ✔
* Responsive UI ✔
* Mobile Support ✔
* Documentation ✔
* Seed Data ✔

---

## 👨‍💻 Author

Pushkar Kumar
Full Stack Developer (MERN Stack)

---
