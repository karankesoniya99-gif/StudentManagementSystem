# StudentManagementSystem


##  Project Overview
This is a **ASP.NET Core Web API** project built for managing student records with secure authentication using **JWT (JSON Web Token)**.  
The project follows a **Layered Architecture** with clean separation of concerns.

---

## ⚙️ Technologies Used
- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server
- JWT Authentication
- Swagger API Documentation
- Serilog Logging

---

## 🏗️ Architecture
The project follows a layered architecture:

- Controllers → API endpoints
- Services → Business logic
- Repositories → Data access layer
- Models → Database entities
- DTOs → Data transfer objects
- Middleware → Exception handling & request logging
- Helpers → JWT token generation

---

## 🔐 Authentication
This project uses JWT-based authentication.

### Login API

---

## 📌 Features

- JWT Authentication
- Secure API Endpoints
- CRUD Operations (Student)
  - Add Student
  - Get All Students
  - Update Student
  - Delete Student
- Global Exception Handling Middleware
- Request Logging Middleware (Serilog)
- Swagger API Documentation
- SQL Server Integration

---

## 🗄️ Database Schema

### Table: Students

| Field        | Type    |
|-------------|--------|
| Id          | int (PK) |
| Name        | string |
| Email       | string |
| Age         | int |
| Course      | string |
| CreatedDate | DateTime |


## 📌 API Endpoints

### Auth
- POST /api/Auth/login

### Students
- GET /api/Student
- POST /api/Student
- PUT /api/Student/{id}
- DELETE /api/Student/{id}

## 🧪 Testing APIs

Use Swagger:



