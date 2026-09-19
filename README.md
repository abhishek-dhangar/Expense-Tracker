# 💰 Expense Tracker

> A Full-Stack Expense Management Application built with **Spring Boot**, **Java**, **MySQL**, **HTML**, **CSS**, and **JavaScript** to help users efficiently track and manage their daily income and expenses.

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Maven](https://img.shields.io/badge/Maven-Build-red)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Managing personal finances can be challenging without proper tracking. This Expense Tracker application provides a simple and intuitive platform where users can:

* Register and log in securely
* Record income and expenses
* View transaction history
* Manage financial records efficiently
* Store data persistently using MySQL

The project follows a clean layered architecture and demonstrates the implementation of RESTful APIs using Spring Boot.

---

## ✨ Features

### 👤 User Management

* User Registration
* User Login Authentication
* User Data Persistence

### 💵 Expense Management

* Add Income Transactions
* Add Expense Transactions
* View Transaction History
* Delete Transactions
* Real-Time Data Retrieval

### 🔗 API-Based Communication

* RESTful Backend Services
* Frontend & Backend Integration
* JSON Data Exchange

---

## 🛠️ Tech Stack

### Backend

* Java 17
* Spring Boot
* Spring Web
* Spring Data JPA
* Hibernate
* Lombok
* Maven

### Frontend

* HTML5
* CSS3
* JavaScript

### Database

* MySQL

### Tools & IDE

* IntelliJ IDEA / VS Code
* MySQL Workbench
* Git & GitHub

---

## 🏗️ Project Architecture

```text
Frontend (HTML/CSS/JS)
          │
          ▼
     REST APIs
          │
          ▼
    Controllers
          │
          ▼
      Services
          │
          ▼
    Repositories
          │
          ▼
      MySQL DB
```

### Layer Responsibilities

#### Controller Layer

Handles incoming HTTP requests and sends responses.

#### Service Layer

Contains business logic and validation.

#### Repository Layer

Interacts with MySQL using Spring Data JPA.

#### Model Layer

Represents User and Transaction entities.

---

## 📂 Project Structure

```text
Expense-Tracker
│
├── Expense-Tracker-Frontend
│   ├── login.html
│   ├── register.html
│   ├── expense_tracker.html
│   ├── script.js
│   └── styles.css
│
├── src/main/java
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   └── ExpenseTrackerApplication.java
│
├── pom.xml
└── README.md
```

---

## ⚙️ Workflow

### Step 1: User Registration

The user creates an account using the registration form.

### Step 2: User Login

Credentials are validated through backend APIs.

### Step 3: Add Transactions

Users can add income or expense records.

### Step 4: Data Storage

Transaction details are stored in MySQL.

### Step 5: View History

Users can fetch and review all recorded transactions.

### Step 6: Manage Records

Users can remove unwanted transaction entries.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/abhishek-dhangar/Expense-Tracker.git
```

### Navigate to Project

```bash
cd Expense-Tracker
```

### Configure MySQL

Update your database credentials inside:

```properties
application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/expense_tracker
spring.datasource.username=root
spring.datasource.password=your_password
```

### Run the Application

```bash
mvn spring-boot:run
```

---

## 📌 API Endpoints

### User APIs

| Method | Endpoint  | Description   |
| ------ | --------- | ------------- |
| POST   | /register | Register User |
| POST   | /login    | User Login    |

### Transaction APIs

| Method | Endpoint           | Description          |
| ------ | ------------------ | -------------------- |
| POST   | /transactions      | Add Transaction      |
| GET    | /transactions      | Get All Transactions |
| DELETE | /transactions/{id} | Delete Transaction   |

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Spring Boot Fundamentals
* REST API Development
* CRUD Operations
* MySQL Integration
* JPA & Hibernate
* Layered Architecture
* Frontend-Backend Communication
* Maven Project Management
* Git & GitHub Workflow

---

## 🔮 Future Enhancements

* JWT Authentication
* Password Encryption
* Monthly Expense Analytics
* Category-Based Expenses
* Charts & Reports
* Budget Planning Module
* Export Data to Excel/PDF
* Mobile Responsive UI

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Abhishek Dhangar**

MCA Student, NIT Kurukshetra

Passionate about Full-Stack Development, Java, Spring Boot, and Software Engineering.

⭐ If you found this project useful, don't forget to give it a star!
