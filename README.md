🍽️ FeastHub – MERN Stack Online Food Ordering System

📌 Abstract

FeastHub is a modern MERN Stack based online food ordering platform designed to simplify the process of discovering restaurants, browsing menus, and placing food orders online. The system provides a user-friendly interface where customers can explore different food categories, view restaurant menus, add items to cart, and place orders easily.

The project demonstrates the implementation of full-stack web development using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It focuses on creating a responsive and scalable web application that improves the online food ordering experience.

This project was developed as a Final Year Group Project for the Computer Science program to demonstrate practical knowledge in modern web technologies, database management, and frontend-backend integration.

🎯 Objectives of the Project

The main objectives of the FeastHub system are:

To develop an online food ordering platform using the MERN stack.

To provide an easy-to-use interface for users to browse and order food.

To implement cart and order management features.

To ensure fast and responsive UI using React and Tailwind CSS.

To demonstrate full-stack development skills including frontend, backend, and database integration.

To deploy the project online using modern cloud platforms like Vercel.

🧩 Problem Statement

Traditional food ordering systems require customers to visit restaurants physically or rely on limited local ordering methods. This creates several problems such as:

Lack of centralized food discovery

Inefficient ordering processes

Limited menu browsing options

Poor user experience

FeastHub aims to solve these problems by providing a centralized digital platform where users can explore restaurants, view menus, and order food quickly and efficiently.

💡 Proposed Solution

FeastHub provides a web-based food ordering system where users can:

Browse available food items

Search for dishes

Add items to a cart

View order details

Experience a responsive modern UI

The system is built using React for frontend, Node.js and Express for backend APIs, and MongoDB for storing application data.

⚙️ System Architecture

The application follows a three-tier architecture:

1️⃣ Presentation Layer (Frontend)

Built using React.js

Provides user interface

Displays food items, menus, and cart

2️⃣ Application Layer (Backend)

Built using Node.js + Express.js

Handles API requests

Processes user actions

3️⃣ Database Layer

MongoDB

Stores user data, food items, orders, and other information

Architecture Flow:

User → React Frontend → Express API → Node.js Server → MongoDB Database
🚀 Features of the System
👤 User Features

User friendly interface

Browse food items

View restaurant menus

Add items to cart

Responsive design

Easy navigation

🛒 Cart Management

Add food items to cart

Remove items from cart

View total price

🍔 Food Browsing

Food categories

Dish details

Menu display

📱 Responsive Design

Mobile friendly UI

Desktop support

🛠️ Technology Stack
Frontend

React.js

TypeScript

Tailwind CSS

Vite

Backend

Node.js

Express.js

Database

MongoDB

Tools

Git

GitHub

Vercel

📂 Project Folder Structure
FeastHub
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── hooks
│   │   ├── assets
│   │   └── utils
│   │
│   ├── public
│   ├── package.json
│   └── vite.config.ts
│
├── backend
│   ├── routes
│   ├── controllers
│   ├── models
│   └── server.js
│
└── README.md
🔄 Working of the System

User visits the website.

React frontend loads the food menu.

Backend APIs fetch data from MongoDB.

User selects food items and adds them to the cart.

Cart updates dynamically using React state management.

Orders can be processed and stored in the database.

⚙️ Installation Guide
Step 1 – Clone the Repository
git clone https://github.com/yourusername/feasthub.git
Step 2 – Navigate to Project Folder
cd feasthub
Step 3 – Install Dependencies

Frontend:

npm install

Backend:

cd backend
npm install
Step 4 – Run the Application

Frontend:

npm run dev

Backend:

node server.js
🌐 Deployment

The frontend of the project is deployed using Vercel.

Live Project Link:

https://feasthub-frontend.vercel.app

Deployment steps:

Push code to GitHub

Connect repository to Vercel

Vercel automatically builds and deploys the application

📊 Advantages of the System

Easy online food ordering

Modern responsive UI

Scalable architecture

Faster ordering process

User friendly interface

⚠️ Limitations

Payment gateway integration not included

Requires internet connection

Admin panel may be added in future versions

🔮 Future Enhancements

Online payment integration

Admin dashboard

Restaurant management panel

Order tracking system

Mobile application version

📚 Learning Outcomes

Through this project we learned:

Full stack web development

MERN stack architecture

API development

Database integration

UI/UX design

Cloud deployment

👨‍💻 Project Team

Akash
B.Tech – Computer Science & Artificial Intelligence

Final Year Group Project
