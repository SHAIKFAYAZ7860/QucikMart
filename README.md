QuickMart – Online Grocery Store

A full-stack e-commerce application built using React (Vite) for the frontend, Spring Boot for the backend, and MySQL with Hibernate for database management.

📌 Project Overview

QuickMart is an online store application with user authentication and a dashboard that displays categories like Mobiles, Laptops, and Headphones after successful login. The backend provides secure API endpoints, while the frontend offers a responsive UI for users.

🛠 Tech Stack
Frontend

React (Vite)

React Router

Axios (for API calls)

Tailwind CSS (for styling)

Backend

Spring Boot

Spring Data JPA (Hibernate)

JWT Authentication

Maven

Database

MySQL

✅ Features

Login System

User authentication using email and password

Dashboard

Displays categories: Mobiles, Laptops, Headphones

Navigation

React Router for page routing

Secure API Integration (Planned)

Spring Boot REST API for authentication and data

📂 Project Structure
Frontend (React + Vite)
quickmart-frontend/
 ├── src/
 │    ├── pages/
 │    │    ├── Login.jsx
 │    │    ├── Dashboard.jsx
 │    ├── App.jsx
 │    └── main.jsx

Backend (Spring Boot)
QuickMart-Backend/
 ├── src/main/java/com/quickmart/
 │    ├── controller
 │    ├── service
 │    ├── model
 │    └── repository
 ├── src/main/resources/
 │    ├── application.properties

⚙️ Installation & Setup
Prerequisites

Node.js (v16+)

Java JDK 17+

MySQL

Maven

1️⃣ Clone Repository
git clone https://github.com/SHAIKFAYAZ7860/QucikMart.git
cd QucikMart

2️⃣ Backend Setup

Navigate to backend folder:

cd QuickMart-Backend


Configure application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/ecom
spring.datasource.username=root
spring.datasource.password=Techno@799
spring.jpa.hibernate.ddl-auto=update


Run Spring Boot backend:

mvn spring-boot:run

3️⃣ Frontend Setup

Navigate to frontend folder:

cd quickmart-frontend


Install dependencies:

npm install


Start Vite development server:

npm run dev


Access app:

http://localhost:5173/

📸 UI Overview

Login Page → Enter credentials

Dashboard Page → Displays Mobiles, Laptops, Headphones after successful login

🚀 Future Enhancements

Add JWT-based authentication with Spring Boot

Fetch product categories dynamically from backend

Create product detail pages

Integrate payment gateway

📧 Contact

Author: Shaik Fayaz
📍 Rayavaram, Andhra Pradesh, India
📞 +91 7995798337
📧 fayazshaik7893@gmail.com
