# 📚 Simple University Student Management App

A console-based Java CRUD application to manage student records using PostgreSQL.

## ✨ Features
- Add new student
- View all students
- View student by ID
- Update student details
- Delete student

## ⚙ Technologies Used
- Java 24
- JDBC (Java Database Connectivity)
- PostgreSQL
- Maven (for build & dependency management)

## 📂 Project Structure
org.example
├── Main.java // Entry point, handles user menu & input
├── DAO
│ └── DAO.java // Data Access Object: CRUD operations
├── model
│ └── Student.java // Student entity/model
└── util
└── DBConnection.java // Utility to connect/close database connection


What I Learned: 
JDBC CRUD operations

Layered architecture (Model, DAO, Utility)

Maven for managing dependencies

Basic SQL & database integration

Handling user input & exceptions in Java
