# PG Management Backend System

A complete backend API for a Paying Guest (PG) / Hostel Management System built using Node.js, Express.js, and MongoDB.

This project is designed to manage PG operations such as tenant management, room allocation, complaints, rent payments, user authentication, and dashboard analytics through secure REST APIs.

It follows a modular backend architecture using routes, controllers, middleware, and database models for scalability and maintainability.

---

## Project Overview

The PG Management Backend System helps PG owners or administrators manage hostel / PG operations digitally.

This backend can be connected with:

- React.js Frontend
- Angular Frontend
- Vue.js Frontend
- Android App
- Admin Dashboard

---

## Features

### Authentication & User Management

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Role-Based Access Control
- Secure Password Hashing

### Tenant Management

- Add Tenant
- Update Tenant Details
- Delete Tenant
- View Tenants

### Room Management

- Add Rooms
- Update Room Details
- Room Availability Tracking
- Room Allocation

### Complaint Management

- Raise Complaint
- View Complaints
- Complaint Status Handling

### Payment Management

- Add Rent Payments
- View Payment History
- Payment Status Tracking

### Dashboard APIs

- Total Rooms
- Total Tenants
- Total Payments
- Management Statistics

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- dotenv
- REST API

---

## Folder Structure

PG-Management-Backend-System/

├── Complaint/  
├── Dashboard/  
├── database/  
├── middleware/  
├── Payment/  
├── Rooms/  
├── Tenant/  
├── Users/  
├── .env.example  
├── .gitignore  
├── package.json  
├── package-lock.json  
├── server.js  
└── README.md

---

## Installation & Setup

### 1. Clone Repository

git clone https://github.com/YOUR_USERNAME/pg-management-backend-system.git

cd pg-management-backend-system

### 2. Install Dependencies

npm install

### 3. Create .env File

Create a file named `.env` in the root folder and add:

PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

### 4. Run Project

npm start

or

npm run dev

---

## Main API Modules

- User APIs
- Tenant APIs
- Room APIs
- Complaint APIs
- Payment APIs
- Dashboard APIs

---

## Sample API Endpoints

POST   /api/users/register

POST   /api/users/login

GET    /api/tenant/all

POST   /api/tenant/add

GET    /api/rooms/all

POST   /api/rooms/add

POST   /api/complaint/add

GET    /api/complaint/all

POST   /api/payment/add

GET    /api/payment/history

---

## How to Use

1. Install Node.js  
2. Clone repository  
3. Run npm install  
4. Create .env file  
5. Add MongoDB connection string  
6. Run npm start  
7. Test APIs using Postman

---

## Future Improvements

- Online Rent Payment Gateway
- Visitor Entry Management
- Email Notifications
- Attendance Tracking
- Mobile App Integration
- Cloud Deployment
- Admin Dashboard Frontend

---

## Why This Project

This project demonstrates:

- REST API Development
- Authentication System
- MongoDB Database Design
- CRUD Operations
- Real World PG Management Logic
- Secure Backend Development
- Git & GitHub Workflow

---

## Author

Syed Shaaz Hassan

---

## License

This project is created for learning, educational, and portfolio purposes.