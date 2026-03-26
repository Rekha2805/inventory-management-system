# 🟣 Inventory Management System

<p align="center">
<img src="https://img.shields.io/badge/Java-17-blue?style=for-the-badge&logo=java"/>
<img src="https://img.shields.io/badge/SpringBoot-3.2-green?style=for-the-badge&logo=springboot"/>
<img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql"/>
<img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

A **Spring Boot-based Inventory Management System** designed to manage products, monitor stock levels, and generate reports efficiently.

✨ Includes **email alerts, role-based authentication, and a modern purple-themed UI**.

---

## 🚀 Features

* Add, Update & Manage Products
* Real-time Stock Updates (+ / −)
* Low Stock Alerts with 📧 Email Notification
* Dashboard with Inventory Analytics
* Role-Based Login (Admin / User)
* CSV Report Export

---

## 🛠️ Tech Stack

* **Backend:** Spring Boot (Java 17)
* **Frontend:** Thymeleaf + Bootstrap
* **Database:** MySQL
* **Security:** Spring Security
* **Build Tool:** Maven

---

## 🔐 Environment Variables

Set the following variables for secure configuration:

```bash
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_email_password
DB_PASSWORD=your_database_password
```

---

## ⚙️ Configuration

### application.properties

```properties
spring.mail.username=${MAIL_USERNAME}
spring.mail.password=${MAIL_PASSWORD}

spring.datasource.password=${DB_PASSWORD}
```

---

## 📧 Email Alert Setup

In `StockAlertService.java`:

```java
private final String ALERT_EMAIL = System.getenv("MAIL_USERNAME");
```

---

## ▶️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/inventory-management-system.git
cd inventory-management-system
```

### Run the Application

* Set environment variables
* Open in IntelliJ / VS Code
* Run `InventoryApplication.java`

### Access

```
http://localhost:8080
```

---

## 🔐 Default Login Credentials

| Role  | Username | Password |
| ----- | -------- | -------- |
| Admin | admin    | admin123 |
| User  | user1    | admin123 |

---

## 📂 Project Structure

```
src/
 ├── controller/
 ├── service/
 ├── repository/
 ├── entity/
 ├── config/
 └── templates/
```

---

## 📄 Documentation

* Agile Documentation
* PPT Presentation

---

## 📜 License

MIT License

---

## 💡 Author

Developed by **Rekha** 💜
