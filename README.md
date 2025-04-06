# 🔐 Spring Boot JWT Authentication

A simple Spring Boot project that demonstrates **JWT-based Authentication** using Spring Security. This project provides a secure way to authenticate and authorize users using JSON Web Tokens (JWT).

---

## 📌 Features

- ✅ User Registration and Login
- 🔐 JWT Token Generation on Login
- 🔁 Token Validation on Each Request
- 🔒 Role-Based Access Control
- 🧰 Spring Security Integration
- ☕ Built with Java 21 and Spring Boot

---

## 🛠 Tech Stack

- Java 21
- Spring Boot
- Spring Security
- JWT (jjwt)
- Maven

---

## 🧪 API Endpoints

| Method | Endpoint            | Description              |
|--------|---------------------|--------------------------|
| POST   | `/api/auth/register` | Register a new user      |
| POST   | `/api/auth/authenticate` | Login and receive JWT |
| GET    | `/api/demo`         | Protected demo endpoint (requires token) |

---

## 📦 Setup & Run

1. **Clone the repository**

```bash
git clone https://github.com/Keshav-chand/springboot-jwt.git
cd springboot-jwt

2. (Optional) Configure your database in `application.properties`.

3. Build and run the application:


# 👨‍💻 Folder Structure
src/main/java/com/example/demo/
│
├── config/                     → Security configuration
├── controller/                 → Handles API requests
├── filter/                     → JWT request filtering
├── model/                      → Entities and DTOs
├── service/                    → Business logic and token service
├── repository/                 → JPA repository interfaces
└── DemoApplication.java        → Main application class

- Register a user via `/api/auth/register`
- Authenticate via `/api/auth/authenticate` to receive a JWT token
- Use the token in the `Authorization` header for secured endpoints:


