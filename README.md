 GroChop - Grocery & Essentials Delivery Platform

GroChop is a full-stack modern web application that enables users to browse, search, and order groceries and daily essentials with ease. Designed to replicate the experience of platforms like Blinkit, GroChop offers a seamless user interface, secure authentication, and robust backend integrations with MySQL.
<h1 align="center">
  👋 Welcome to <span style="color:#16a34a;">GroChop</span> – Your Daily Essentials in a Go! 🛒
</h1>

<p align="center">
  <img src="[https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="200" alt="Waving Grocery GIF](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdjJoNWdpMXk2Y215OHEzbDJ6aW1lemVpeXNkbzFsaHU5YXc0cXM0MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MRJNuE2rPe9ro7Cc1x/giphy.gif)" />
</p>

<p align="center">
  GroChop is a modern, full-stack grocery & essentials delivery platform that brings the supermarket to your doorstep! 🚪📦 <br />
  Built with using <strong>React, Vite, Tailwind CSS, Node.js, Express, and MySQL</strong>.
</p>

<p align="center">
  <a href="#🚀-features">Explore Features</a> • 
  <a href="#🛠️-tech-stack">Tech Stack</a> • 
  <a href="#📦-installation">Installation</a>
</p>

🚀 Features

 🔍 User-Facing
- 🧑‍💼 User Registration & Login (with email verification)
- 🛍️ Add to Cart, View Cart & Place Orders
- 🧾 Order History & Real-Time Status
- 🔎 Product Search & Filtering
- 📦 Product Categories (Fruits, Veggies, etc.)

🛠️ Admin Panel
- 👤 Admin Authentication
- 📂 Product & Category Management
- 📦 Order Management Dashboard

 💻 Technical Highlights
- ✅ JWT-based Authentication
- 📡 RESTful API using Express.js
- 💾 MySQL + Sequelize ORM for database
- 📈 Responsive UI using React + Tailwind CSS
- ⚡ Superfast development with Vite
- 

 ⚙️ Tech Stack

 🖥️ Frontend
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- JavaScript (ES6+)
- Axios for API calls

🌐 Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [Sequelize ORM](https://sequelize.org/)


## 🔐 Authentication & Security
- Password hashing using `bcrypt`
- Token-based auth with `jsonwebtoken`
- Role-based access (User/Admin)
- Secure environment variables using `.env`


 📁 Project Structure

bash
GROCHOP/
│
├── client/                 # React + Vite frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── ...
│
├── server/                 # Express.js backend
│   ├── config/             # Sequelize & DB config
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
│
├── .env                   # Environment variables
└── README.md
