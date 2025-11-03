# Task Management System

A full-stack web application built using **Spring Boot**, **React**, and **MySQL** that allows users to register, log in, and manage their daily tasks efficiently.  
This project demonstrates full CRUD operations, authentication, REST API development, and frontend–backend integration.

---

## ✅ Features

### 🔐 Authentication

- User Registration (Sign Up)
- User Login
- Backend-authenticated routes

### ✅ Task Management

- Create new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Real-time UI updates

### 💾 Backend Features

- Spring Boot REST APIs
- MySQL database integration
- Spring Data JPA repository layer
- Input validation & centralized exception handling

### 🎨 Frontend Features

- React components
- Axios for API calls
- Forms for login, signup, and task operations
- Bootstrap UI styling

---

## ✅ Tech Stack

### **Frontend (React)**

- React JS
- Axios
- Bootstrap / CSS

### **Backend (Spring Boot)**

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Validation
- MySQL
- Maven

---

## ✅ Project Structure

Task-Management-System/  
│  
├── backend/  
│ ├── src/main/java/... (Spring Boot Code)  
│ ├── src/main/resources/  
│ └── pom.xml  
│  
└── frontend/  
 ├── src/  
 ├── public/  
 └── package.json

---

## ✅ How to Run the Project

### **1️⃣ Backend Setup (Spring Boot)**

1. Open the **backend** folder in your IDE (IntelliJ / Eclipse / VS Code).

2. Create the MySQL database:
   ```sql
   CREATE DATABASE taskdb;
   ```
3. Update your DB username/password in:
   backend/src/main/resources/application.properties
4. Install backend dependencies:

```bash
mvn clean install
5. Run the backend server:
mvn spring-boot:run

✅ Backend will run at:
http://localhost:8080

2️⃣ Frontend Setup (React)
1. Navigate to frontend:
cd frontend
2. Install packages:
npm install
3. Start the frontend:
npm start
✅ App will open at:
http://localhost:3000

✅ API Overview
Method	   Endpoint	            Description
POST	  /api/auth/register	  Register new user
POST	  /api/auth/login	      Login and get token
GET	    /api/tasks	          Fetch all tasks
POST	  /api/tasks	          Create new task
PUT	    /api/tasks/{id}	      Update task
DELETE	/api/tasks/{id}	      Delete task
```
