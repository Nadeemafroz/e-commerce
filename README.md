# 🛒 MERN E-Commerce App

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A full-featured e-commerce platform built with MongoDB, Express, React, and Node.js.

## ✨ Features

### User Features
- ✅ User registration & login (JWT authentication)
- 🔍 Product browsing with search and filters
- 🛒 Shopping cart functionality
- 💳 Secure checkout process
- 📦 Order history tracking

### Admin Features
- 👔 Admin dashboard
- 📊 Product management (CRUD operations)
- 📝 Order management
- 📈 Sales analytics

## 🚀 Tech Stack

### Frontend
- React.js with Hooks
- React Router v6
- Context API
- Axios
- Bootstrap/SCSS

### Backend
- Node.js & Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Bcrypt.js
- Multer

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/mern-ecommerce.git
cd mern-ecommerce
Install dependencies

bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
Environment Setup

Create .env files:

server/.env

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
client/.env

REACT_APP_API_URL=http://localhost:5000/api
Run the application

bash
# Backend (from server directory)
npm run dev

# Frontend (from client directory)
npm start
📂 Project Structure
mern-ecommerce/
├── client/               # React Frontend
│   ├── public/           # Static files
│   ├── src/              # React source
│   │   ├── assets/       # Images, fonts
│   │   ├── components/   # UI components
│   │   ├── context/      # State management
│   │   ├── pages/       # Page components
│   │   ├── utils/        # Helper functions
│   │   └── App.js       # Main component
│   └── package.json
│
├── server/               # Express Backend
│   ├── config/           # Config files
│   ├── controllers/      # Route controllers
│   ├── models/           # MongoDB models
│   ├── routes/           # API routes
│   ├── middleware/       # Custom middleware
│   ├── uploads/          # File uploads
│   └── server.js        # Entry point
│
└── README.md
🌐 Deployment
Frontend:
Deploy to Vercel, Netlify, or Firebase Hosting

Backend:
Deploy to Render, Railway, or Heroku

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

📄 License
This project is licensed under the MIT License.

✍️ Author: Your Name
📧 Email: your.email@example.com
🔗 GitHub: @your-username