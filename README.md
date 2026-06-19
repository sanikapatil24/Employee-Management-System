# Employee Management System

A Full Stack Employee Management System built using React.js and Spring Boot. The application provides secure JWT-based authentication, role-based authorization, and complete Employee CRUD operations through a responsive user interface and RESTful APIs.

---

## Project Overview

This project is designed to manage employee records securely. Users can authenticate using JWT tokens and perform employee management operations such as adding, updating, viewing, and deleting employee records.

The backend is developed using Spring Boot, Spring Security, JWT, Hibernate/JPA, and MySQL, while the frontend is built with React.js, Axios, React Router, and Bootstrap.

---

##  Features

### Authentication & Authorization

- JWT Authentication
- Secure Login System
- Spring Security Integration
- Role-Based Access Control
- Protected API Endpoints

### Employee Management

- Add Employee
- View All Employees
- Update Employee Details
- Delete Employee
- Employee Validation

### Backend Features

- RESTful APIs
- Spring Boot
- Spring Security
- JWT Token Generation & Validation
- Hibernate / JPA
- MySQL Database Integration
- Global Exception Handling
- Input Validation

### Frontend Features

- React.js UI
- React Router Navigation
- Axios API Integration
- Bootstrap Styling
- Responsive Design

---

## Tech Stack

### Frontend

- React.js
- React Router DOM
- Axios
- Bootstrap
- JavaScript
- HTML5
- CSS3

### Backend

- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA
- Hibernate
- Maven

### Database

- MySQL

### Tools

- Git
- GitHub
- Postman
- VS Code
- Eclipse

---

## System Architecture

```text
React Frontend
      │
      ▼
 REST APIs
      │
      ▼
Spring Boot Backend
      │
      ▼
Spring Security + JWT
      │
      ▼
 Hibernate / JPA
      │
      ▼
    MySQL
```

---

## Screenshots

### Login Page
<img width="960" height="479" alt="image" src="https://github.com/user-attachments/assets/7be4024e-2862-4a63-9d53-d7e6c93f4b31" />

---

### Employee Dashboard

<img width="959" height="482" alt="image" src="https://github.com/user-attachments/assets/d3bd0eba-9031-496b-bc31-5703eac35456" />

---

### Add Employee

<img width="960" height="478" alt="image" src="https://github.com/user-attachments/assets/a4bebf9c-2baa-4956-8dd8-fda9af2e85bd" />


---

### Update Employee

<img width="960" height="472" alt="image" src="https://github.com/user-attachments/assets/7a56c751-887f-4497-bf39-77e1ee1ec927" />


---

##  Authentication Flow

1. User enters username and password.
2. Backend validates credentials.
3. JWT token is generated.
4. Token is returned to the frontend.
5. Frontend stores token.
6. Token is sent in Authorization Header for protected requests.

### Authorization Header

```http
Authorization: Bearer <JWT_TOKEN>
```

---

##  REST API Endpoints

### Authentication APIs

| Method | Endpoint | Description |
|----------|----------|----------|
| POST | `/auth/login` | User Login |

---

### Employee APIs

| Method | Endpoint | Description |
|----------|----------|----------|
| GET | `/employees` | Get All Employees |
| GET | `/employees/{id}` | Get Employee By ID |
| POST | `/employees` | Add Employee |
| PUT | `/employees/{id}` | Update Employee |
| DELETE | `/employees/{id}` | Delete Employee |

---

## Database Schema

### User Table

| Column | Type |
|----------|----------|
| id | BIGINT |
| username | VARCHAR |
| password | VARCHAR |
| role | VARCHAR |

---

### Employee Table

| Column | Type |
|----------|----------|
| id | BIGINT |
| name | VARCHAR |
| email | VARCHAR |
| department | VARCHAR |
| salary | DOUBLE |

---

## Future Enhancements

- Refresh Tokens
- Forgot Password
- Email Notifications
- Employee Search
- Pagination
- Sorting & Filtering
- Cloud Deployment (AWS/Azure)

---

##  Learning Outcomes

Through this project, I gained practical experience with:

- Spring Boot Development
- REST API Design
- Spring Security
- JWT Authentication
- Hibernate & JPA
- MySQL Integration
- React Development
- Axios API Calls
- Git & GitHub
- Full Stack Application Development

---

##  Author

**Sanika Patil**

Computer Science Engineering Student

---

## ⭐ If you found this project useful, please consider giving it a star.
