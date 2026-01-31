# 🎓 Student Management System

A full-stack **Student Management System** built using **Spring Boot** that allows users to perform CRUD operations (Create, Read, Update, Delete) on student records.

This project follows **MVC architecture** and uses **Spring Data JPA with Hibernate** for database interaction.

---

## 🚀 Features

- Add new students
- View list of students
- Update student details
- Delete student records
- Clean MVC based architecture
- Automatic table creation using Hibernate

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- HTML
- Thymeleaf

### Database
- MySQL

### Build Tool
- Maven

---

## 🧠 Architecture Used

- **Controller** – Handles HTTP requests  
- **Service** – Contains business logic  
- **Repository** – Interacts with database using JPA  
- **Entity** – Maps Java objects to database tables  

---
## 📁 Project Structure
```

student-management-system-springboot
│── src
│ ├── main
│ │ ├── java
│ │ │ └── controller
│ │ │ └── service
│ │ │ └── repository
│ │ │ └── entity
│ │ └── resources
│ │ ├── templates
│ │ └── application.properties
│── pom.xml
│── README.md

```
---

## ⚙️ How to Run the Project

### Prerequisites
- Java 17 or above
- Maven
- MySQL running

---

### Step 1: Clone the Repository

```bash
git clone https://github.com/Revannath-Khodade/student-management-system-springboot.git
```
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password
```
mvn spring-boot:run
```
mvn spring-boot:run
```
## 🎯 Interview Ready Explanation

> This is a Spring Boot based Student Management System that performs CRUD operations using MVC architecture.  
> Spring Data JPA with Hibernate handles database operations, and Thymeleaf is used for frontend rendering.

---

## 👨‍💻 Author

**Revannath Khodade**  
GitHub: https://github.com/Revannath-Khodade
