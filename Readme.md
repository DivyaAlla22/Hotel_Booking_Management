🏨 TripByte Hotel Management System

TripByte Hotel is a robust full-stack web application designed for seamless hotel room management and guest reservations. It features a modern React frontend and a powerful Spring Boot backend to handle real-time availability and secure booking operations.

🚀 Key Features

Admin Room Management
Admins can add, edit, and delete rooms with high-quality photo uploads.

Real-Time Booking
Users can check room availability and book rooms instantly.

Booking Confirmation Logic
Generates a unique and secure confirmation code (e.g., 5240496379) for every successful booking.

Availability Validation
Prevents double bookings by validating date overlaps and providing clear user feedback.

JWT Authentication
Secure login and registration using JWT, protecting administrative routes.

🛠️ Tech Stack
Frontend

React.js

Axios

Vite

React Router

Bootstrap

Backend

Java

Spring Boot

Spring Security (JWT)

Maven

Database

MySQL / PostgreSQL

📂 Project Structure
TripByte-Hotel/
├── frontend/            # React + Vite application
│   ├── src/             # Components, Hooks, and Services
│   └── public/          # Static assets
└── backend/             # Spring Boot application
    ├── src/             # Controllers, Services, and Entities
    └── pom.xml          # Project dependencies

⚙️ Installation & Setup
1️⃣ Backend Setup

Navigate to the backend folder

Update database credentials in:

src/main/resources/application.properties


Increase file upload limits for room images:

spring.servlet.multipart.max-file-size=10MB
spring.servlet.multipart.max-request-size=10MB


Run the backend:

mvn spring-boot:run

2️⃣ Frontend Setup

Navigate to the frontend folder

Install dependencies:

npm install


Start the development server:

npm run dev


Access the application at:

http://localhost:5173

📸 Screenshots 

Room Management – Admins can add and manage room types with pricing and images
<img width="1919" height="970" alt="image" src="https://github.com/user-attachments/assets/3ad16aca-3a3d-4087-aec7-f0acb6b13df5" />

<img width="1910" height="975" alt="image" src="https://github.com/user-attachments/assets/7c36cbbd-cecc-4023-ab70-61a9ab9b6c72" />



Booking Success – Users receive instant confirmation codes after successful booking

🎯 Purpose of the Project

This project was developed to gain hands-on experience in Full Stack Development, RESTful APIs, authentication, and frontend–backend integration using modern technologies.
