# Employee Management System

A full-stack CRUD application built using **Spring Boot, PostgreSQL, and React.js**.  
This application allows users to create, view, update, and delete employee records through a modern web interface.

---

## Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- REST API

### Frontend
- React.js
- Axios
- Bootstrap

### Database
- PostgreSQL

### Tools
- IntelliJ IDEA
- VS Code
- Postman
- Git & GitHub

---

## Project Structure
employee-management-system
│
├── crudapp (Spring Boot backend)
│ ├── controller
│ ├── service
│ ├── repository
│ ├── entity
│
├── frontend
│ └── crud-frontend (React frontend)
│
└── README.md

---

## Features

- Add new employees
- View employee list
- Edit employee details
- Delete employee records
- RESTful API architecture
- Responsive UI with Bootstrap

---

## API Endpoints

| Method | Endpoint | Description |
|------|------|-------------|
| GET | `/api/employees` | Get all employees |
| GET | `/api/employees/{id}` | Get employee by ID |
| POST | `/api/employees` | Create new employee |
| PUT | `/api/employees/{id}` | Update employee |
| DELETE | `/api/employees/{id}` | Delete employee |

---

## Running the Project

### 1 Backend (Spring Boot)

Navigate to backend folder:
