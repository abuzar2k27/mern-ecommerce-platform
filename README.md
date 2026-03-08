# 🛒 MERN E-Commerce Platform

A full-stack E-Commerce web application built using the **MERN stack (MongoDB, Express, React, Node.js)** with secure authentication, Stripe payment integration, Cloudinary image management, and a dedicated Admin Dashboard.

This project demonstrates real-world e-commerce architecture including role-based access control, JWT authentication, secure payment processing, and scalable REST API design.

---

# 🏗 Architecture Overview

## System Architecture

![Architecture Diagram](screenshots/Archecture%20Diagram.png)

## JWT Authentication Flow

![JWT Authentication Flow](screenshots/JWT%20authentication%20FLow%20Diagram.png)

## Stripe Payment Flow

![Stripe Payment Flow](screenshots/Stripe%20Payment%20Flow%20Diagram.png)

---

# ✨ Features

## 🛍 Customer Frontend

- User Registration & Login
- Secure Password Hashing (bcrypt)
- JWT-based Authentication
- Product Browsing & Filtering
- Product Detail Pages
- Add to Cart & Quantity Management
- Stripe Checkout Integration
- Order History & Tracking
- Fully Responsive UI

---

## 🛠 Admin Dashboard

- Admin Authentication
- Add / Edit / Delete Products
- Upload Product Images (Cloudinary)
- Order Management
- User Management
- Role-Based Access Control

---

# 🖼 Application Screenshots

## 🏠 Home Page
![Home Page](screenshots/Home-Page-Design.png)

## 📦 Collection Page
![Collection](screenshots/Collection.png)

## 🛒 Product Page
![Product Page](screenshots/Product-Page.pngg)

## 🛍 Your Cart
![Your Cart](screenshots/Your-Cart.png)

## 💳 Checkout & Delivery
![Checkout](screenshots/Checkout-and-Delivery-page.png)

## 📜 My Orders
![My Orders](screenshots/My-Orders.png)

## ℹ About Page
![About](screenshots/About.png)

## 📞 Contact Us
![Contact](screenshots/Contact-Us.png)

## 🛠 Admin Panel (Adding Products)
![Admin Panel](screenshots/Admin-Panel.png)

---

# 🏗 Tech Stack

## Frontend
- React (Vite)
- React Router
- Axios
- Context API

## Backend
- Node.js
- Express.js
- JWT Authentication
- bcrypt (Password Hashing)
- Stripe SDK
- Cloudinary SDK

## Database
- MongoDB (Mongoose ODM)

---

# 🔐 Authentication Flow

- User logs in with email and password
- Backend verifies credentials
- JWT token is generated
- Token stored on client-side
- Protected routes validated via middleware

---

# 💳 Payment Integration

- Backend creates Stripe Checkout Session
- Frontend redirects to Stripe Hosted Payment Page
- Stripe processes payment securely
- Backend updates order status upon confirmation

---

# 📂 Project Structure
MERN-Ecommerce/
│
├── admin/ # React Admin Dashboard
├── backend/ # Node + Express REST API
├── frontend/ # React Customer Store
├── screenshots/ # Application Screenshots & Diagrams
│
└── README.md


---

# ⚙️ Environment Variables

Create `.env` files inside each folder.

## Backend (`backend/.env`)

MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=admin@example.com

ADMIN_PASSWORD=adminpassword


## Frontend (`frontend/.env`)

VITE_BACKEND_URL=http://localhost:4000


## Admin (`admin/.env`)

VITE_BACKEND_URL=http://localhost:4000


---

# 🛠 Installation & Setup

## 1️⃣ Clone Repository

git clone https://github.com/yourusername/your-repository-name.git

cd your-repository-name


## 2️⃣ Install Dependencies

Backend:

cd backend
npm install


Frontend:

cd frontend
npm install


Admin:

cd admin
npm install


## 3️⃣ Run Project

Start Backend:

cd backend
npm run server


Start Frontend:

cd frontend
npm run dev


Start Admin:

cd admin
npm run dev


Frontend runs on:

http://localhost:5173


---

# 🧠 Architecture Highlights

- REST API-based client-server architecture  
- Stateless JWT authentication  
- Middleware-based route protection  
- Cloud-based image storage (Cloudinary)  
- Secure third-party payment integration (Stripe)  
- Role-based access control for admin panel  

---

# 🚀 Future Improvements

- Product reviews & ratings  
- Email verification  
- Inventory management  
- Dashboard analytics  
- Refresh token implementation  
- Redis caching  

---

# 👨‍💻 Author

**Muhammad Abuzar**  
Full-Stack MERN Developer