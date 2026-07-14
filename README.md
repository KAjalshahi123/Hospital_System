# 🏥 Hospital Management System

A comprehensive **Hospital Management System** built with **Spring Boot**, **Spring Data JPA**, **MySQL**, **Docker**, and **Docker Compose**. This project helps manage patients, doctors, appointments, and billing through REST APIs.

---

## 🚀 Tech Stack

- ☕ Java 17
- 🌱 Spring Boot 3
- 🗄️ Spring Data JPA (Hibernate)
- 🐬 MySQL 8
- 📦 Maven
- 🐳 Docker
- 🐳 Docker Compose
- 🔗 REST API
- 💻 IntelliJ IDEA
- 📮 Postman

---

# 📂 Project Architecture

```text
                    🏥 Hospital Management System
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
        ▼                      ▼                      ▼
   👨‍⚕️ Doctor           🧑 Patient          📅 Appointment
        │                      │                      │
        └──────────────┬───────┘                      │
                       ▼                              │
                 💰 Billing Module                   │
                       │                              │
                       ▼                              ▼
                 🗄️ MySQL Database  ←──── Spring Data JPA
                               │
                               ▼
                        🐳 Docker Container
```

---

# ✨ Features

## 👨‍⚕️ Doctor Management

- ➕ Add Doctor
- ✏️ Update Doctor
- ❌ Delete Doctor
- 🔍 View Doctor Details
- 📋 Get All Doctors

---

## 🧑 Patient Management

- ➕ Register Patient
- ✏️ Update Patient
- ❌ Delete Patient
- 🔍 View Patient Details
- 📋 Get All Patients

---

## 📅 Appointment Management

- 📅 Schedule Appointment
- ✏️ Update Appointment
- ❌ Cancel Appointment
- 🔍 Get Appointment by ID
- 📋 View All Appointments

---

## 💰 Billing Management

- 💳 Generate Bill
- ✏️ Update Bill
- ❌ Delete Bill
- 📄 View Bill Details
- 📋 View All Bills

---

# 📁 Project Structure

```text
Hospital
│
├── src
│   ├── controller
│   ├── service
│   ├── repository
│   ├── models
│   └── config
│
├── Dockerfile
├── docker-compose.yml
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

# 🗄️ Database

Database Name

```text
hospital_db
```

Tables

- 👨‍⚕️ Doctor
- 🧑 Patients
- 📅 Appointment
- 💰 Bill

---

# 🌐 REST APIs

## 👨‍⚕️ Doctor APIs

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/Doctor` |
| GET | `/api/v1/Doctor/{id}` |
| POST | `/api/v1/Doctor` |
| PUT | `/api/v1/Doctor/{id}` |
| DELETE | `/api/v1/Doctor/{id}` |

---

## 🧑 Patient APIs

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/patients` |
| GET | `/api/v1/patients/{id}` |
| POST | `/api/v1/patients` |
| PUT | `/api/v1/patients/{id}` |
| DELETE | `/api/v1/patients/{id}` |

---

## 📅 Appointment APIs

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/Appointment` |
| GET | `/api/v1/Appointment/{id}` |
| POST | `/api/v1/Appointment` |
| PUT | `/api/v1/Appointment/{id}` |
| DELETE | `/api/v1/Appointment/{id}` |

---

## 💰 Billing APIs

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/Bill` |
| GET | `/api/v1/Bill/{id}` |
| POST | `/api/v1/Bill` |
| PUT | `/api/v1/Bill/{id}` |
| DELETE | `/api/v1/Bill/{id}` |

---

# 🐳 Docker Support

Build Docker Image

```bash
docker build -t hospital-app .
```

Run using Docker Compose

```bash
docker compose up --build
```

Run in Background

```bash
docker compose up -d
```

Stop Containers

```bash
docker compose down
```

---

# ▶️ Run Project Locally

Clone Repository

```bash
git clone https://github.com/KAjalshahi123/Hospital_System.git
```

Move into Project

```bash
cd Hospital
```

Build Project

```bash
./mvnw clean package
```

Run Application

```bash
java -jar target/Hospital-0.0.1-SNAPSHOT.jar
```

---

# 🧪 API Testing

Use:

- 📮 Postman
- 🌩️ Thunder Client

Base URL

```text
http://localhost:8080
```

Example

```text
GET http://localhost:8080/api/v1/patients
```

---

# 👩‍💻 Author

**Kajal Shahi**

- 💼 Java Full Stack Developer
- 🌱 Spring Boot Backend Developer
- 🐳 Docker Enthusiast

GitHub

https://github.com/KAjalshahi123

LinkedIn

https://www.linkedin.com/in/kajal-shahi1314/

---

# ⭐ If you like this project

⭐ Star this repository

🍴 Fork it

💙 Happy Coding!
