🛒 CampusCart – Campus Marketplace Web Application

CampusCart is a full-stack campus-focused e-commerce web application designed to help students buy and sell items securely within their campus community. The platform supports user authentication, product listings, RESTful APIs, and cloud deployment, following modern web development and DevOps practices.

📌 Project Overview

CampusCart provides a centralized marketplace where students can:

Create product listings

Browse campus-specific items

Securely authenticate users

Manage listings using REST APIs

This project demonstrates end-to-end full-stack development, including backend API design, authentication, deployment, and CI/CD readiness.

🚀 Key Features

🔐 JWT-based User Authentication

🛍 Create & Manage Product Listings

🌐 RESTful API Architecture

🧾 Secure Request Handling

☁ Cloud Deployment (AWS & Render)

🔄 CI/CD-ready Project Structure

📦 Modular Backend Design

🖥 User-friendly Web Interface

🧑‍💻 Tech Stack
Frontend

HTML

CSS

JavaScript

Backend

Node.js

Express.js

REST APIs

JWT Authentication

Database

MongoDB

Deployment & DevOps

AWS EC2 – Backend hosting (previously deployed)

AWS S3 – Frontend hosting (previously deployed)

Render – Current live deployment

CI/CD Pipeline – GitHub-based workflow readiness

🏗 System Architecture
Client (Browser)
   ↓
Frontend UI
   ↓
REST APIs (Express.js)
   ↓
Authentication (JWT)
   ↓
MongoDB Database

🔐 Authentication Flow

User registers/logs in

Server generates JWT token

Token is sent with API requests

Backend validates token before allowing access

'''📂 Project Structure
CampusCart/
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── index.js
│
├── public/
│   ├── css/
│   ├── js/
│   └── html/
│
├── package.json
├── README.md
└── .env'''

⚙ Installation & Setup
Prerequisites

Node.js

MongoDB

Git

Steps
# Clone repository
git clone https://github.com/dp2426-NAU/Campuscart.git

# Navigate into project
cd Campuscart

# Install dependencies
npm install

# Run the server
npm start


Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

🌍 Deployment Details

Initially deployed using AWS S3 (frontend) and AWS EC2 (backend)

AWS services were terminated to optimize cost

Currently deployed on Render for live access

CI/CD pipeline structure prepared for automated deployments

📈 Future Enhancements

🛒 Shopping cart & checkout system

💳 Payment gateway integration

📍 Campus-based filtering

📱 Responsive mobile-first UI

🧑‍💼 Admin dashboard

🔔 Notifications system

🎓 Academic Context

Project Type: Academic & Portfolio Project

Institution: Northern Arizona University (NAU)

Course Focus: Full-Stack Development, Cloud Deployment, REST APIs

🤝 Contributors

Developer: Divyasri Pothuraju

Role: Full-Stack Development, Cloud Deployment, API Design

📄 License

This project is created for educational Purpose.
