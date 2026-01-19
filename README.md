# 🔐 Secure User Authentication System

**Prodigy InfoTech – Full-Stack Web Development Internship (Task 01)**

## 📌 Project Overview
This project implements a **secure user authentication system** using **Spring Boot**, **Spring Security**, **Thymeleaf**, and **MySQL**.  
Users can register, log in securely, and access protected routes based on authentication and roles.

This project is developed as part of **Task 01** of the **Full-Stack Web Development Internship at Prodigy InfoTech**.

---

## 🚀 Features
- User Registration with validation
- Secure Login & Logout
- Password encryption using **BCrypt**
- Session-based authentication
- Role-based access control (USER / ADMIN)
- Protected routes using Spring Security
- MySQL database integration
- MVC architecture with Thymeleaf

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot, Spring Security
- **Frontend:** Thymeleaf, HTML, CSS
- **Database:** MySQL
- **ORM:** Hibernate / JPA
- **Build Tool:** Maven

---

## 📂 Project Structure
src/main/java
└── com.prodigy.auth
├── controller
├── model
├── repository
├── security
└── service

src/main/resources
├── templates
├── static/css
└── application.properties




## 🔐 Security Implementation
- Passwords are hashed using **BCryptPasswordEncoder**
- Spring Security manages authentication and authorization
- Unauthorized users are redirected to the login page
- Role-based access restricts admin-only endpoints





