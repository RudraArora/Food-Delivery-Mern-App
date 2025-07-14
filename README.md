# 🍔 Food Delivery MERN App

A full-stack food ordering application built with the **MERN stack**, where users can browse food items, add them to a cart, and place orders. The app includes user authentication, a simple UI, and a connected backend to handle food data and order management.

---

## 🚀 Features

- 🔐 User authentication and authorization (login/signup)
- 🛍️ Browse food items from various restaurants
- 🛒 Add items to cart (basic checkout flow)
- 📦 Basic cart management (order tracking coming soon)
- 🌐 Fully responsive frontend using React.js
- 🌍 RESTful APIs using Express.js and MongoDB

---

## 🧑‍💻 Tech Stack

| Frontend | Backend | Database | Other |
|---------|--------|----------|--------|
| React.js | Node.js | MongoDB | Express.js |
| CSS   | JWT Auth | Mongoose | Dotenv |

---

## ⚙️ Installation

### 1. Clone the repository

git clone https://github.com/RudraArora/Food-Delivery-Mern-App.git
cd Food-Delivery-Mern-App

### 2. Install server dependencies
 - cd server
 - npm install

### 3. Install client dependencies
 - cd ../client
 - npm install

## 🌐 Running the App Locally
Start backend (Node.js + Express)
 - cd server
 - npm start

Start frontend (React)
 - cd ../client
 - npm start

## 🔑 Environment Variables
 - Create a .env file in the server directory with the following:
 - PORT=5000
 - MONGO_URI=your_mongo_connection_string
 - JWT_SECRET=your_jwt_secret
 - Add .env file in .gitignore.
