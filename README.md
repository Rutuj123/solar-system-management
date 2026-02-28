# 🌞 Solar System Management Platform

Enterprise-grade Full Stack Web Application built using Spring Boot and Angular.

---

## 🚀 Tech Stack

### 🔧 Backend
- Java 17
- Spring Boot
- Spring Security (JWT Authentication)
- Hibernate / JPA
- MySQL

### 🎨 Frontend
- Angular 20
- Reactive Forms
- Route Guards
- HTTP Interceptors
- Role-Based Authorization

---

## 🏗 Architecture

- Layered Architecture (Controller → Service → Repository)
- DTO Pattern
- Global Exception Handling
- JWT-based Authentication
- RESTful API Design
- Secure Route Guards

---

## 🔐 Features

- Admin Login
- Role-Based Access Control
- Entry Management
- Quotation Management
- Order Creation with Dropdown Integration
- Secure API Endpoints (401 / 403 handling)
- Token Interceptor
- Protected Admin Dashboard

---

## 📂 Project Structure
solar-system-management/
│
├── backend/
│ ├── src/
│ ├── pom.xml
│ └── Dockerfile
│
├── frontend/
│ ├── src/
│ ├── angular.json
│ └── package.json
│
└── README.md

## 🛠️ Setup Instructions

### 🔹 Backend
cd backend
mvn clean install
mvn spring-boot:run
Runs on:
http://localhost:8080

### 🔹 Frontend
cd frontend
npm install
ng serve
Runs on:
http://localhost:4200

## 🔑 Authentication Flow
1. User logs in
2. Backend generates JWT token
3. Token stored in localStorage
4. Angular HTTP Interceptor attaches token to every request
5. Spring Security validates token
6. Access granted based on role

   ## 🐳 Docker Support (Optional)
docker-compose up --build

## 👩‍💻 Author
Rutuja Kolhe  
Full Stack Java Developer
