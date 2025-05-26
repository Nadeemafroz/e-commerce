
# E-Commerce App

A full-featured e-commerce platform built using the MERN stack (MongoDB, Express.js, React, Node.js). The app enables users to browse, search, and purchase products, while providing admins with tools to manage products, users, and orders efficiently. It features secure authentication, real-time cart updates, category-based filtering, and integrated payment gateways for smooth checkout experiences.


## Features

### 🔐 **User Authentication (JWT)**
Secure login system with user/admin role-based access using JWT and bcrypt.

**Login demo:**  
![App Screenshot](https://res.cloudinary.com/dmdgp4yf9/image/upload/v1748272821/e-commerce/auth.gif)

### 🔍 **Product Search & Filtering**
Search for products and filter them by category in real-time.

**Search Demo:**  
![App Screenshot](https://res.cloudinary.com/dmdgp4yf9/image/upload/v1748272889/e-commerce/search.gif)

### 🛒 **Dynamic Cart Management**
Add/remove products and update quantities with real-time cart totals.

**Cart Demo:**  
![App Screenshot](https://res.cloudinary.com/dmdgp4yf9/image/upload/v1748272845/e-commerce/cart.gif)

### 💳 **Payment Integration**
Supports Stripe for secure online payments.

**Payment Demo:**  
![App Screenshot](https://res.cloudinary.com/dmdgp4yf9/image/upload/v1748272864/e-commerce/payment.gif)

### 🛠️ **Admin Panel**
Admins can manage products, users, and orders through a dedicated dashboard.

**Review Demo:**  
![App Screenshot](https://res.cloudinary.com/dmdgp4yf9/image/upload/v1748272793/e-commerce/admin.gif)



## 📦 Installation

### 💻 Frontend (User)

1. Navigate to the `frontend` folder.  
2. Install dependencies:

   ```bash
   npm install
3.Start the development server:
   ```
   npm run dev
   ```

### 🛠️ Backend (Shared for User & Admin)

1. Navigate to the `backend` folder.  
2. Install dependencies:

   ```bash
   npm install
   ```
3.Create a .env file and add the required environment variables:
  - MongoDB Atlas URI
  - Cloudinary credentials (cloud name, API key, secret)
  - Stripe API key
4. Start the backend server:
    ```bash
   npm run dev
   ```

### 🧑‍💼 Admin Frontend

1. Navigate to the `admin` folder.  
2. Install dependencies:

   ```bash
   npm install
3.Start the development server:
   ```
   npm run dev
   ```
## 🛠️ Tech Stack

### 🧩 Frontend
- React  
- React Router  
- Axios  
- Bootstrap

### 🔧 Backend
- Node.js  
- Express.js  
- JWT (Authentication)  
- bcrypt (Password Encryption)

### 🗄️ Database
- MongoDB  
- Mongoose

### 💳 Payment Integration
- Stripe  
- PayPal

### 🛠️ Tools Used
- Visual Studio Code  
- Postman  
- MongoDB Atlas  
- Cloudinary  



## 📬 Contact

If you have any questions, suggestions, or feedback, feel free to reach out:

- **Name**: Nadeem Afroz  
- **Email**: nadeemafroz12@gmail.com  
- **LinkedIn**: [linkedin.com/in/nadeem-afroz](https://www.linkedin.com/in/nadeem-afroz/)
