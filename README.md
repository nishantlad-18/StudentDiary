# 📚 Student Diary

A simple and user-friendly **Student Diary Management System** designed to help students manage their academic information, daily activities, notes, tasks, and important reminders in one place.

---

## 🎯 Project Objective

The main objective of this project is to provide students with a digital diary where they can organize their academic and study-related information easily.

Instead of maintaining everything in a physical diary, students can use this application to manage their information digitally.

---

## ✨ Features

- 👤 Student Profile Management
- 📝 Add and Manage Notes
- 📅 Manage Daily Activities
- ✅ Task Management
- 📚 Subject-wise Information
- 📌 Important Reminders
- 📖 Academic Information Management
- 🔍 View and Manage Student Records
- 💾 Store data digitally
- 🖥️ Simple and user-friendly interface

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Java
- Spring Boot

### Database
- MySQL

### Tools
- IntelliJ IDEA / Eclipse
- Git
- GitHub
- Postman

---

## 🏗️ Project Architecture

```text
                 Student Diary
                      │
          ┌───────────┴───────────┐
          │                       │
       Frontend                Backend
          │                       │
    HTML/CSS/JS             Spring Boot
                                  │
                          ┌───────┴───────┐
                          │               │
                       REST API       Business Logic
                          │               │
                          └───────┬───────┘
                                  │
                              MySQL DB
```

---

## 📂 Project Structure

```text
Student-Diary/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── ...
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│
├── README.md
├── pom.xml
└── .gitignore
```

---

## 🔄 Application Flow

```text
Student
   ↓
Login / Access Application
   ↓
Student Dashboard
   ↓
┌───────────────┬───────────────┐
│               │               │
Notes         Tasks         Reminders
│               │               │
└───────────────┴───────────────┘
                ↓
           Database
```

---

## 🗄️ Database

The application uses **MySQL** for storing student-related information.

Possible entities include:

- Student
- Subject
- Notes
- Tasks
- Reminders
- Activities

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

Open the project in:

```text
IntelliJ IDEA / Eclipse
```

### 3. Configure Database

Create a MySQL database and update the database configuration in:

```text
application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_diary
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
```

### 4. Run the application

Run the Spring Boot main class.

### 5. Open the application

Open the application in your browser using the configured localhost port.

---

## 🧪 Testing

The APIs can be tested using:

- Postman
- Browser
- Application UI

Testing includes:

- Adding student information
- Updating records
- Deleting records
- Retrieving records
- Managing notes and tasks

---

## 🔮 Future Enhancements

The following features can be added in future versions:

- 🔐 User Authentication
- 🔑 Role-based Access
- 📱 Responsive Mobile Interface
- 📊 Student Dashboard
- 🔔 Notification System
- ☁️ Cloud Deployment
- 📎 File/Document Upload
- 📅 Calendar Integration
- 🔒 Spring Security & JWT
- 🐳 Docker Deployment

---

## 📌 Learning Outcomes

Through this project, I practiced:

- Java Programming
- Object-Oriented Programming
- Database Connectivity
- CRUD Operations
- Backend Development
- REST API Development
- Spring Boot
- MySQL
- Git & GitHub
- Project Structure and Documentation

---

## 👨‍💻 Author

**Nishant Lad**

MCA Student | Aspiring Java Developer

---

## ⭐ Project Goal

The goal of this project is to build a practical application while improving my skills in **Java, Spring Boot, SQL, backend development, and software engineering**.

> **Learn → Build → Test → Improve → Deploy 🚀**

---

## 🏷️ GitHub Repository Description

A digital Student Diary Management System for managing academic information, notes, tasks, activities, and reminders.

## 🔖 GitHub Topics

java, spring-boot, mysql, student-diary, backend, rest-api, crud, html, css, javascript, github
