🎓 Student Management System



A full-stack \*\*Student Management System\*\* built using \*\*Spring Boot\*\* that allows users to perform CRUD operations (Create, Read, Update, Delete) on student records.



This project follows \*\*MVC architecture\*\* and uses \*\*Spring Data JPA with Hibernate\*\* for database interaction.



---



\## 🚀 Features



\- Add new students

\- View list of students

\- Update student details

\- Delete student records

\- MVC based clean architecture

\- Database auto table creation using Hibernate



---



\## 🛠️ Tech Stack



\### Backend

\- Java

\- Spring Boot

\- Spring MVC

\- Spring Data JPA

\- Hibernate



\### Frontend

\- HTML

\- Thymeleaf



\### Database

\- MySQL



\### Build Tool

\- Maven



---



\## 🧠 Architecture Used







\- \*\*Controller\*\*: Handles HTTP requests

\- \*\*Service\*\*: Contains business logic

\- \*\*Repository\*\*: Interacts with database using JPA

\- \*\*Entity\*\*: Maps Java objects to database tables



---



\## 📁 Project Structure





student-management-system-springboot

│── src

│ ├── main

│ │ ├── java

│ │ │ └── controller, service, repository, entity

│ │ └── resources

│ │ ├── templates

│ │ └── application.properties

│── pom.xml

│── README.md













---



\## ⚙️ How to Run the Project



\### Prerequisites

\- Java 17+ installed

\- Maven installed

\- MySQL running



---



\### Step 1: Clone the Repository



```bash

git clone https://github.com/Revannath-Khodade/student-management-system-springboot.git









Step 2: Configure Database



Update application.properties:



spring.datasource.url=jdbc:mysql://localhost:3306/student\_db

spring.datasource.username=root

spring.datasource.password=your\_password









Step 3: Run the Application

mvn spring-boot:run









Step 4: Access the Application



Open browser and go to:



http://localhost:8080/students









```powershell

git add README.md

git commit -m "Add professional README file"

git push

























