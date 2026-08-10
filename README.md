# 🚀 PrabandhX

### **Full-Stack Organization Management System**

A modern enterprise-grade platform for managing **organizations, projects, teams, tasks, files, and collaboration** with secure role-based authentication.

<p align="center">

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.5-6DB33F?style=for-the-badge\&logo=springboot\&logoColor=white)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)](https://react.dev/)
[![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)](https://www.oracle.com/java/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)](https://www.mysql.com/)
[![JWT](https://img.shields.io/badge/JWT-Authentication-black?style=for-the-badge\&logo=jsonwebtokens)](https://jwt.io/)
[![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](LICENSE)

</p>

---

# 📖 Overview

**PrabandhX** is a complete **Organization Management System** built with **Spring Boot** and **React**, designed to simplify project management, task tracking, team collaboration, and file sharing within organizations.

The application provides a secure, scalable, and intuitive platform featuring **JWT authentication**, **role-based authorization**, real-time dashboards, project collaboration, audit logs, and efficient team management.

---

# ✨ Key Features

## 🔐 Authentication & Security

* JWT Authentication
* Spring Security Integration
* Role-Based Authorization
* Secure Password Encryption
* Protected API Endpoints
* Session Management

---

## 👥 User Management

* Create, Update & Delete Users
* User Search & Filtering
* Role Assignment
* User Profiles
* Account Management

---

## 📊 Dashboard

* Organization Statistics
* User Analytics
* Project Overview
* Task Progress
* Activity Timeline
* Interactive Charts

---

## 📁 Project Management

* Create & Manage Projects
* Project Collaboration
* Project Members
* Status Tracking
* Deadlines
* Project Overview

---

## ✅ Task Management

* Create Tasks
* Assign Tasks
* Due Date Tracking
* Priority Levels
* Status Updates
* Progress Monitoring

---

## 🤝 Team Collaboration

* Invite Members
* Permission Management
* Accept / Reject Invitations
* Collaborator Roles
* Shared Workspaces

---

## 📂 File Management

* Upload Files
* Download Files
* File Sharing
* Version History
* Project Attachments

---

## 📈 Activity Logs

* Complete Audit Trail
* User Activity Tracking
* Date Filtering
* Action Filtering
* System History

---

# 🏗️ System Architecture

```text
React + Vite
        │
        ▼
REST API (Spring Boot)
        │
        ▼
Spring Security + JWT
        │
        ▼
Spring Data JPA
        │
        ▼
MySQL Database
```

---

# 🛠️ Tech Stack

## Backend

* Java 21
* Spring Boot 3.2.5
* Spring Security
* Spring Data JPA
* JWT
* Hibernate
* Maven

### Database

* MySQL 8

### Frontend

* React 18
* Vite
* React Router DOM
* Axios
* Framer Motion
* Recharts
* React Hot Toast

### Development Tools

* Git
* GitHub
* IntelliJ IDEA
* VS Code
* Postman

---

# 📂 Project Structure

```text
PrabandhX/
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── resources/
│   │   │   └── application.properties
│   │   └── test/
│   ├── pom.xml
│   └── mvnw
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── layouts/
│   │   └── assets/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
└── LICENSE
```

---

# 🚀 Getting Started

## Prerequisites

Ensure you have installed:

* Java 21+
* Maven 3.9+
* Node.js 18+
* npm
* MySQL 8+

---

# ⚙️ Backend Setup

### Clone Repository

```bash
git clone https://github.com/Auro993/PrabandhX.git

cd PrabandhX/backend
```

---

### Create Database

```sql
CREATE DATABASE prabandhx;
```

---

### Configure Database

Update **application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/prabandhx
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

---

### Run Backend

```bash
./mvnw spring-boot:run
```

Backend runs at

```text
http://localhost:8080
```

---

# 💻 Frontend Setup

Navigate to frontend

```bash
cd ../frontend
```

Install dependencies

```bash
npm install
```

Start development server

```bash
npm run dev
```

Frontend runs at

```text
http://localhost:5173
```

---

# 🔑 Default Accounts

| Role       | Email                                                 | Password   |
| ---------- | ----------------------------------------------------- | ---------- |
| 👑 Admin   | [admin@prabandhx.com](mailto:admin@prabandhx.com)     | admin123   |
| 📋 Manager | [manager@prabandhx.com](mailto:manager@prabandhx.com) | manager123 |
| 👤 User    | [user@prabandhx.com](mailto:user@prabandhx.com)       | user123    |

---

# 📡 REST API

| Module         | Endpoint             | Method                    |
| -------------- | -------------------- | ------------------------- |
| Authentication | `/api/auth/login`    | POST                      |
| Authentication | `/api/auth/register` | POST                      |
| Users          | `/api/users`         | GET / POST / PUT / DELETE |
| Projects       | `/api/projects`      | GET / POST / PUT / DELETE |
| Tasks          | `/api/tasks`         | GET / POST / PUT / DELETE |
| Files          | `/api/files`         | GET / POST / DELETE       |
| Activity       | `/api/activity`      | GET                       |

---

# 🎯 Role Permissions

## 👑 Admin

* Full System Access
* User Management
* Project Management
* Task Management
* Activity Monitoring
* System Administration

---

## 📋 Manager

* Manage Assigned Projects
* Assign Tasks
* Team Collaboration
* Invite Members
* Project Reports

---

## 👤 User

* View Assigned Tasks
* Update Task Status
* Upload Files
* Download Files
* View Personal Activity

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push to GitHub

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📄 License

Distributed under the **MIT License**.

See the **LICENSE** file for more information.

---

# 👨‍💻 Author

**Aurosmita Sahoo**

📧 Email: [aurosmitasahoo4@gmail.com](mailto:aurosmitasahoo4@gmail.com)

🐙 GitHub: https://github.com/Auro993

💼 LinkedIn: https://linkedin.com/in/aurosmita-sahoo

---

# 🙏 Acknowledgments

* Spring Boot
* React
* Spring Security
* JWT
* MySQL
* Vite
* Recharts
* Open Source Community

---

<div align="center">

### ⭐ If you found this project helpful, please consider giving it a Star.

**Built with ❤️ using Spring Boot & React**
</div>
