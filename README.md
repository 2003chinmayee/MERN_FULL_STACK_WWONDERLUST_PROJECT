# 🌍 Wanderlust – Full-Stack Travel Listing Web Application

Wanderlust is a **full-stack MERN application** inspired by Airbnb, designed for exploring and sharing travel destinations.  
Users can create listings, view others’ listings, leave reviews, and manage their accounts — all with secure authentication and database integration.

---

## 🧠 Table of Contents
- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Installation & Setup](#️-installation--setup)
- [Environment Variables](#-environment-variables)
- [Folder Details](#-folder-details)
- [Screenshots](#️-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🌐 Overview

Wanderlust is built using the **MERN Stack (MongoDB, Express.js, React, Node.js)**.  
It serves as a travel destination listing platform where users can:
- Sign up / Login securely
- Create and manage property listings
- Upload images
- View other listings
- Post reviews
- Edit or delete their own listings

This project is inspired by Apna College’s MERN tutorial and expanded with additional UI and backend improvements.

---

## 🧩 Tech Stack

**Frontend**
- HTML5, CSS3, EJS (Embedded JavaScript Templates)
- Bootstrap for UI components
- Vanilla JavaScript

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB Atlas (Cloud-hosted NoSQL database)

**Authentication & Security**
- Passport.js (Local Strategy)
- bcrypt for password hashing
- Express-Session for user sessions

**File Upload & Storage**
- Cloudinary for image hosting
- Multer for handling uploads

---

## 🚀 Features

✅ User Authentication (Register, Login, Logout)  
✅ Add / Edit / Delete Travel Listings  
✅ Add Reviews and Ratings  
✅ Image Upload via Cloudinary  
✅ Responsive UI with Bootstrap  
✅ Authorization – Only the creator can edit/delete their own listings  
✅ MongoDB integration for persistent data  
✅ Flash messages for feedback (success/error)  
✅ RESTful Routing & MVC folder structure  

---

## 🗂️ Project Structure

wanderlust/
│
├── app.js # Main server file (entry point)
├── package.json # Dependencies and scripts
├── /views # EJS templates for frontend
│ ├── layouts/
│ ├── listings/
│ └── reviews/
│
├── /models # Mongoose models (User, Listing, Review)
├── /routes # Express route files
├── /public # Static files (CSS, JS, images)
├── /utils # Custom middleware & helpers
└── .env # Environment variables 

---


## ⚙️ Installation & Setup

Follow these steps to run the project locally 👇

### 1️⃣ Clone the repository
```bash
git clone https://github.com/2003chinmayee/MERN_FULL_STACK_WWONDERLUST_PROJECT.git


### 2️⃣ Navigate to the project folder
cd MERN_FULL_STACK_WWONDERLUST_PROJECT/wanderlust

### 3️⃣ Install dependencies
npm install

### 4️⃣ Setup environment variables

Create a .env file inside the root folder and add the following:

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_secret
MAP_TOKEN=your_mapbox_token
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
PORT=8080

###5️⃣ Start MongoDB (if local)

If using MongoDB locally:

mongod


If using MongoDB Atlas, ensure the .env file has your correct ATLASDB_URL.

###6️⃣ Run the application
nodemon app.js


or

node app.js


The app will start at:
👉 http://localhost:8080

### 🧰 Folder Details
Folder	Description
models/	Contains all Mongoose schemas for Listings, Reviews, and Users
routes/	Express routes for listing, reviews, and user authentication
views/	EJS templates used for rendering UI pages
public/	Static assets (CSS, JS, Images)
utils/	Middleware and helper functions (authentication, validation, etc.)


###👩‍💻 Author

👤 Chinmayee Patil
📧 [YourEmail@example.com
]
🌐 GitHub Profile

💼 Full Stack Developer | MERN | Passionate Learner

⭐ If you like this project, please give it a star on GitHub!






