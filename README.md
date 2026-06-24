# 🎓 Role Based Student Management System

A web-based Student Management System developed using Spring Boot and MySQL that provides secure authentication and role-based access for Students and Teachers.

The application allows users to register, login, and access features based on their assigned roles.

---

## 🚀 Features

- User Registration and Login
- Role-Based Authentication & Authorization
- Student Portal
- Teacher Portal
- Secure Password Handling using Spring Security
- Form Validation
- Database Integration using MySQL
- MVC Architecture
- Dynamic Pages using Thymeleaf

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate

### Frontend
- HTML
- CSS
- Thymeleaf

### Database
- MySQL

### Build Tool
- Maven

---

## 📂 Project Structure

```text
Student-Management-System
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.burak.studentmanagement
│   │   │       ├── controller
│   │   │       ├── service
│   │   │       ├── dao
│   │   │       ├── entity
│   │   │       ├── config
│   │   │       └── user
│   │   │
│   │   └── resources
│   │       ├── templates
│   │       ├── static
│   │       └── application.properties
│
├── pom.xml
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shalinib805-sbpd/role_based_student_management.git
```

Move into project:

```bash
cd role_based_student_management
```

---

## 🗄️ Database Setup

Open MySQL and create database:

```sql
CREATE DATABASE student;
```

Update:

`src/main/resources/application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3307/student
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```

---

## ▶️ Run Application

Using Maven:

```bash
mvn clean install
mvn spring-boot:run
```

Or run:

```text
StudentManagementApplication.java
```

---

## 🌐 Application URLs

Home:

```text
http://localhost:8081/
```

Registration:

```text
http://localhost:8081/register/showRegistrationForm
```

Login:

```text
http://localhost:8081/showMyLoginPage
```

---

## 👥 Roles

### Student
- Register Account
- Login
- Access Student Dashboard

### Teacher
- Register Account
- Login
- Access Teacher Dashboard

---

## 🔐 Security

- Spring Security Authentication
- Password Encryption
- Role Based Authorization
- Protected Routes

---

## 📌 Future Improvements

- Admin Dashboard
- Email Verification
- Profile Management
- Attendance System
- REST API Integration

---

## 👩‍💻 Author

Shalini B

GitHub:
https://github.com/shalinib805-sbpd

---

⭐ If you like this project, give it a star.
