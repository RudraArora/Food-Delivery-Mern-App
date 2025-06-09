# 🍔 Food Delivery MERN App

A full-stack food delivery application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project allows users to browse restaurants, order food, and track their deliveries — with admin capabilities for managing menu and orders.

---

## 🚀 Features

- 🔐 User authentication and authorization (login/signup)
- 🛍️ Browse food items from various restaurants
- 🛒 Add to cart and place orders
- 📦 Order tracking
- 🧑‍🍳 Admin dashboard to manage menu and orders
- 🌐 Fully responsive frontend using React.js
- 🌍 RESTful APIs using Express.js and MongoDB

---

## 🧑‍💻 Tech Stack

| Frontend | Backend | Database | Other |
|---------|--------|----------|--------|
| React.js | Node.js | MongoDB | Express.js |
| Axios   | JWT Auth | Mongoose | Dotenv |
| Tailwind / CSS |  |  | CORS, Bcrypt |

---

## ⚙️ Installation

### 1. Clone the repository

git clone https://github.com/RudraArora/Food-Delivery-Mern-App.git
cd Food-Delivery-Mern-App

##2. Install server dependencies
 - cd server
 - npm install

##3. Install client dependencies
 - cd ../client
 - npm install

🌐 Running the App Locally
 - Start backend (Node.js + Express)
 - cd server
 - npm start

Start frontend (React)
 - cd ../client
 - npm start

🔑 Environment Variables
 - Create a .env file in the server directory with the following:
 - PORT=5000
 - MONGO_URI=your_mongo_connection_string
 - JWT_SECRET=your_jwt_secret
 - Add .env file in .gitignore.
