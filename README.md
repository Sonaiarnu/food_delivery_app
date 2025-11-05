# 🍔 Food Delivery App - Full Stack (Frontend + Backend)

The **Food Delivery App** is a complete full-stack web application built with **React (Frontend)** and **Node.js + Express.js (Backend)**.
It allows users to browse food items, add them to a cart, place orders, and manage their profiles — all powered by secure authentication and a responsive user interface.

---



## 🧩 Features

### 🌐 Frontend (React)

* **User Authentication** – Secure login and registration using JWT.
* **Cart Functionality** – Add, remove, and manage items before checkout.
* **Search Bar** – Quickly find food items from the menu.
* **Location Input** – Enter delivery location for better order management.
* **Order History** – View previously placed orders.
* **Responsive UI** – Designed for both mobile and desktop.

### ⚙️ Backend (Node.js + Express)

* **User Authentication** – Handles registration and login with **bcrypt.js** for password hashing and **JWT** for session management.
* **RESTful APIs** – Endpoints for managing users, food items, and orders.
* **MongoDB Database** – Efficient and scalable NoSQL storage.
* **Secure Operations** – Uses tokens for protected routes and session validation.

---

## 🛠️ Technologies Used

| Layer        | Technologies                                 |
| :----------- | :------------------------------------------- |
| **Frontend** | React, Context API, Axios, CSS               |
| **Backend**  | Node.js, Express.js, MongoDB, JWT, bcrypt.js |
| **Hosting**  | Render (for both frontend and backend)       |

---

## ⚡ Installation and Setup

### 🖥️ Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/devvib/food_delivery_app_backend.git
   cd food_delivery_app_backend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the backend server:

   ```bash
   npm start
   ```
4. Server runs at:

   ```
   http://localhost:5000
   ```

---

### 💻 Frontend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/devvib/food_delivery_app_frontend.git
   cd food_delivery_app_frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the React app:

   ```bash
   npm start
   ```
4. App runs at:

   ```
   http://localhost:3000
   ```

---

## 🔒 Authentication Flow

1. User registers → Password is hashed using **bcrypt.js**.
2. On login → A **JWT token** is generated and stored locally.
3. Subsequent requests → Authenticated using the JWT in headers.

---




---

## 🧠 Developer Notes

* Designed for scalability and maintainability.
* Uses **Context API** instead of Redux for lightweight state management.
* Hosted using Render’s free tier (may need to wake backend manually).
* Can be extended with features like admin dashboards, live order tracking, and payment integration.

---



✨ *“A deliciously fast and secure food delivery experience — from code to cuisine!”*
