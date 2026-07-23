# SME Accounting System

> **Enterprise Accounting Management System**
> Java Web × Spring Boot × MySQL × Bootstrap 5 × Docker

---

# 📖 Introduction

SME Accounting System is a modern web-based accounting platform designed specifically for **small and medium-sized enterprises (SMEs)**. It provides an intuitive accounting workflow, financial reporting, account management, and administrative functions to simplify daily bookkeeping.

The system adopts a **Responsive Web Design (RWD)** architecture, allowing users to access it seamlessly from desktop computers, tablets, and smartphones.

---

# ✨ Features

## Front-end (User Portal)

* Dashboard
* Income Management
* Expense Management
* Transaction Records
* Account Management
* Category Management
* Financial Reports
* Monthly Profit Analysis
* Cash Flow Analysis
* Receipt / Invoice Number
* Search & Filter
* Excel Export
* Responsive Design (Desktop / Tablet / Mobile)

---

## Back-end (Administration)

* Administrator Dashboard
* User Management
* Role Management
* Permission Control
* Income Category Management
* Expense Category Management
* Company Information
* System Settings
* Operation Logs
* Database Initialization

---

# 📊 Dashboard

The dashboard provides:

* Total Income
* Total Expense
* Net Profit
* Cash Balance
* Monthly Income Trend
* Monthly Expense Trend
* Expense Category Distribution
* Recent Transactions

---

# 🖥️ System Architecture

```
Browser
     │
     ▼
Spring Boot MVC
     │
 ┌───────────────┐
 │ Spring Security│
 └───────────────┘
     │
Spring Data JPA
     │
     ▼
MySQL Database
```

---

# 🛠 Technology Stack

| Technology      | Version |
| --------------- | ------- |
| Java            | 21      |
| Spring Boot     | 3.x     |
| Spring MVC      | ✔       |
| Spring Security | ✔       |
| Spring Data JPA | ✔       |
| Thymeleaf       | ✔       |
| Bootstrap       | 5       |
| MySQL           | 8       |
| Maven           | Latest  |
| Docker          | Latest  |

---

# 📂 Project Structure

```
SME-Accounting-System
│
├── src
│   ├── main
│   │   ├── java
│   │   │    ├── controller
│   │   │    ├── service
│   │   │    ├── repository
│   │   │    ├── entity
│   │   │    ├── dto
│   │   │    ├── config
│   │   │    └── security
│   │   │
│   │   ├── resources
│   │   │    ├── templates
│   │   │    ├── static
│   │   │    └── application.yml
│   │
│   └── test
│
├── docker-compose.yml
├── Dockerfile
├── pom.xml
└── README.md
```

---

# 🔐 Login

### Administrator

```
Username : admin
Password : admin123
```

### Staff

```
Username : staff
Password : staff123
```

> Change the default passwords immediately after deployment.

---

# 📱 Responsive Design

Supported devices:

* Desktop
* Laptop
* Tablet
* Smartphone

Compatible browsers:

* Google Chrome
* Microsoft Edge
* Firefox
* Safari

---

# 📈 Financial Reports

The system supports:

* Income Report
* Expense Report
* Profit & Loss Statement
* Monthly Statistics
* Category Analysis
* Cash Flow Summary

---

# 🔒 Security Features

* Spring Security Authentication
* Role-Based Access Control (RBAC)
* Password Encryption (BCrypt)
* Session Management
* CSRF Protection
* SQL Injection Prevention (JPA)
* XSS Protection
* Server-side Validation

---

# 🐳 Docker Deployment

## Build

```bash
docker compose build
```

## Run

```bash
docker compose up -d
```

Open:

```
http://localhost:8080
```

---

# 💻 Local Development

Requirements:

* Java 21
* Maven
* MySQL 8

Run:

```bash
mvn spring-boot:run
```

---

# 🗄 Database

Default database:

```
MySQL 8
```

Main tables:

* users
* roles
* accounts
* income_categories
* expense_categories
* transactions
* companies
* audit_logs

---

# 🚀 Future Roadmap

* AI Financial Analysis
* OCR Receipt Recognition
* Electronic Invoice Integration
* QR Code Payment
* REST API
* Mobile App
* Multi-company Support
* Multi-language Interface
* Cloud Backup
* BI Dashboard
* Budget Planning
* Tax Estimation
* AI Accounting Assistant

---

# 📄 License

This project is intended for educational, research, and commercial customization purposes.

---

# 👨‍💻 Author

Developed with:

* Java
* Spring Boot
* Bootstrap 5
* MySQL
* Docker
* Responsive Web Design (RWD)

Designed for modern SMEs to achieve efficient, secure, and user-friendly accounting management.
