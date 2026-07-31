<div align="center">

# 🎬 Movie Ticket Management System

### 🍿 Book • Explore • Experience Movies Effortlessly

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=3000&pause=1000&color=FF6B00&center=true&vCenter=true&width=800&lines=Full+Stack+Movie+Ticket+Booking+Application;Built+with+Spring+Boot+%7C+Hibernate+%7C+MySQL;MVC+Architecture+%7C+Thymeleaf+%7C+Bootstrap;Designed+and+Developed+by+Lokesh+Chaudhari" />

<br>

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green?style=for-the-badge&logo=springboot)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-Framework-brightgreen?style=for-the-badge)
![Hibernate](https://img.shields.io/badge/Hibernate-ORM-brown?style=for-the-badge&logo=hibernate)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-blue?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-Database-00758F?style=for-the-badge&logo=mysql)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-Template-darkgreen?style=for-the-badge)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap)
![Maven](https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven)


</div>

---

# 🌟 Overview

The **Movie Ticket Management System** is a modern full-stack web application inspired by real-world cinema booking platforms. It allows users to browse movies, explore theatres, check show timings, book tickets, and manage reservations through a clean and responsive interface.

The application follows the **Spring Boot MVC Architecture** with a layered backend, making it scalable, maintainable, and easy to extend.

---

# 🚀 Project Highlights

- 🎬 Complete Movie Booking Platform
- 👤 User Registration & Authentication
- 🏢 Theatre Management
- 🎟 Ticket Booking System
- 💺 Seat Availability Management
- 📅 Show Scheduling
- ⚙️ Admin Dashboard
- 📦 Layered MVC Architecture
- 🔄 CRUD Operations
- 🗄 MySQL Database Integration
- 📱 Responsive Bootstrap UI
- 🧩 Clean Code Structure

---

# ✨ Features

## 👤 User Module

- Register New Account
- Login Authentication
- Browse Movies
- View Movie Details
- Explore Theatres
- Check Show Timings
- Book Tickets
- View Booking History

---

## 🎬 Movie Module

- Add Movies
- Update Movie Details
- Delete Movies
- View Movie List

---

## 🏢 Theatre Module

- Add Theatre
- Update Theatre
- Delete Theatre
- Manage Theatre Information

---

## 🎟 Show Module

- Create Shows
- Update Show Timings
- Manage Available Seats
- View Show Schedule

---

## ⚙️ Admin Module

- Manage Movies
- Manage Theatres
- Manage Shows
- Manage Bookings
- Monitor System Data

---

# 🏗 System Architecture

```mermaid
flowchart LR

A[👤 User]

A --> B[🎮 Controller]

B --> C[⚙️ Service Layer]

C --> D[🗄 Repository]

D --> E[🔄 Hibernate ORM]

E --> F[(🐬 MySQL Database)]

F --> E

E --> D

D --> C

C --> B

B --> G[🎨 Thymeleaf UI]

G --> A
```

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Java 17 |
| Backend | Spring Boot, Spring MVC |
| ORM | Hibernate |
| Data Access | Spring Data JPA |
| Frontend | HTML5, CSS3, Bootstrap 5, Thymeleaf |
| Database | MySQL |
| Build Tool | Maven |
| IDE | Eclipse IDE |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```
MovieTicketManagement
│
├── src
│   ├── controller
│   ├── entity
│   ├── repository
│   ├── service
│   ├── serviceimpl
│   ├── dto
│   ├── exception
│   ├── config
│   └── resources
│       ├── static
│       └── templates
│
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

# ⚙️ Installation Guide

### Clone Repository

```bash
git clone https://github.com/Lok997/movie-ticket-management-system-springboot.git
```

### Open Project

```bash
cd movie-ticket-management-system-springboot
```

### Configure Database

Update your **application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/movie_ticket_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### Run Application

```bash
mvn spring-boot:run
```

Open your browser:

```
http://localhost:8080
```

---

# 📸 Project Screenshots

> Add screenshots of your application here.
<img width="1840" height="1023" alt="Screenshot 2026-07-31 202302" src="https://github.com/user-attachments/assets/59cc3b3e-9020-4c38-8534-f9caca235fc0" />
<img width="1807" height="991" alt="Screenshot 2026-07-31 202325" src="https://github.com/user-attachments/assets/9473235f-f08c-486e-9f3b-7f2b9da1608a" />
<img width="1800" height="877" alt="Screenshot 2026-07-31 202338" src="https://github.com/user-attachments/assets/e7c7d256-c1dd-4d9d-be54-5fff0574deaf" />
<img width="1277" height="946" alt="Screenshot 2026-07-31 202417" src="https://github.com/user-attachments/assets/13981e8c-71e9-440f-ad0d-338cb409742d" />
<img width="1901" height="1016" alt="Screenshot 2026-07-31 202509" src="https://github.com/user-attachments/assets/7d8abdf4-018f-4f71-b4f2-52e980ad2f8f" />
> <img width="1376" height="973" alt="Screenshot 2026-07-31 202519" src="https://github.com/user-attachments/assets/98b8d431-92bf-427a-84d3-2aa76e7cc01b" />
<img width="1802" height="547" alt="Screenshot 2026-07-31 202434" src="https://github.com/user-attachments/assets/b34ab4a6-cd08-49a8-b8cb-10e7a4d1756b" />




---

# 🚀 Future Enhancements

- 💳 Online Payment Gateway
- 📷 QR Code Ticket Generation
- 📧 Email Notifications
- ⭐ Ratings & Reviews
- 🔍 Advanced Movie Search
- 🎯 Interactive Seat Selection
- 🌙 Dark Mode
- 📱 Mobile Responsive Improvements

---

# 📚 Learning Outcomes

Through this project, I strengthened my understanding of:

- Spring Boot Development
- MVC Architecture
- Spring Data JPA
- Hibernate ORM
- CRUD Operations
- Thymeleaf Integration
- MySQL Database Design
- Exception Handling
- Layered Architecture
- Git & GitHub Workflow
- Maven Project Management

---

# 👨‍💻 Developer

## Lokesh Chaudhari

**Aspiring Java Backend Developer | Spring Boot Developer | Full Stack Java Learner**

📧 Email: **lokeshchaudhari997@gmail.com**

🔗 GitHub: **https://github.com/Lok997**

---

<div align="center">

## ⭐ If you found this project helpful, please consider giving it a Star!

**Thank you for visiting this repository. Happy Coding! 🚀**

</div>
