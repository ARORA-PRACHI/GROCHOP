<h1 align="center">
  👋 Welcome to GroChop – Your Daily Essentials in a Go! 🛒
</h1>

<p align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdjJoNWdpMXk2Y215OHEzbDJ6aW1lemVpeXNkbzFsaHU5YXc0cXM0MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MRJNuE2rPe9ro7Cc1x/giphy.gif" width="280" alt="Welcome Animation">
</p>

<p align="center">
  GroChop is a full-stack modern grocery & essentials delivery platform that brings the supermarket to your doorstep. <br/>
  <strong>Built using:</strong> React, Vite, Tailwind CSS, Node.js, Express, and MySQL.
</p>

<p align="center">
  <a href="#features">🚀 Explore Features</a> • 
  <a href="#tech-stack">🧰 Tech Stack</a> • 
  <a href="#installation">📦 Installation</a>
</p>

---

🚀 Features

 🔍 User-Facing
- 👤 User Registration & Login (Email Verification)
- 🛍️ Add to Cart, View Cart & Place Orders
- 📦 Order History & Real-Time Status
- 🔎 Product Search & Filtering
- 🧃 Product Categories (Fruits, Veggies, etc.)

 🛠️ Admin Panel
- 🔐 Admin Authentication
- 📋 Product & Category Management
- 📊 Order Management Dashboard

---

 🧰 Tech Stack

 🖥️ Frontend
- ⚛️ [React](https://reactjs.org/)
- ⚡ [Vite](https://vitejs.dev/)
- 🎨 [Tailwind CSS](https://tailwindcss.com/)
- 📜 JavaScript (ES6+)
- 🔗 Axios for API calls

 🔧 Backend
- 🧩 [Node.js](https://nodejs.org/)
- 🚂 [Express.js](https://expressjs.com/)
- 🛢️ [MySQL](https://www.mysql.com/)
- 🔄 [Sequelize ORM](https://sequelize.org/)

---

 🔐 Authentication & Security

- 🔒 Password hashing using `bcrypt`
- 🔑 JWT-based Authentication
- 🧑‍💼 Role-based Access Control (User/Admin)
- 📁 Secure `.env` for Environment Variables

---

 🗂️ Project Structure

```bash
GROCHOP/
├── client/         # React + Vite Frontend
│   ├── src/
│   ├── components/
│   └── pages/
├── server/         # Express Backend
│   ├── config/     # DB + Sequelize
│   ├── controllers/
│   ├── models/
│   └── routes/
├── .env
└── README.md
