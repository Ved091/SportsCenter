# SportsCenter - Service Management Platform (Spring Boot + React)

A scalable full-stack e-commerce platform for sports equipment, built using **Spring Boot (Java 21)** and **React (TypeScript)**. The system supports product discovery, authentication, cart management, and order processing with a focus on performance, modular architecture, and production-ready design.

---

## 🚀 Key Features

- 🔐 JWT-based Authentication & Authorization  
- 🛒 Redis-backed Shopping Cart for fast session handling  
- 📦 Order Management System with relational persistence  
- 🔎 Product Search, Filtering, Pagination & Sorting  
- ⚡ Scalable REST APIs for frontend-backend communication  
- 📊 Swagger/OpenAPI documentation  

---

## 🧠 System Architecture

- **Backend**: Spring Boot (Layered Architecture - Controller, Service, Repository)  
- **Frontend**: React + TypeScript (Component-based architecture)  
- **Database**: MySQL (Relational schema)  
- **Caching**: Redis (Basket/session storage)  
- **Auth**: JWT (Stateless security)  
- **Infra**: Docker-based setup  

---

## 🛠️ Tech Stack

### Backend
- Java 21, Spring Boot  
- Spring Data JPA, Hibernate  
- Spring Security + JWT  
- MySQL, Redis  
- MapStruct, Lombok  

### Frontend
- React 18, TypeScript  
- Redux Toolkit  
- Material UI  
- Axios, React Router  

### DevOps & Tools
- Docker, Docker Compose  
- Swagger (OpenAPI)  
- Maven  

---

## 📦 Core Modules

- **Auth Service** → Login, JWT generation, user validation  
- **Product Service** → Search, filtering, pagination  
- **Basket Service** → Redis-based cart management  
- **Order Service** → Order creation and history  

---

## ⚙️ Getting Started

### Prerequisites
- Java 21  
- Node.js 18+  
- Docker  

### Setup

```bash
git clone https://github.com/Ved091/SportsCenter.git
cd SportsCenter

# Start database services
cd docker
docker-compose up -d

# Run backend
./mvnw spring-boot:run

# Run frontend
cd client
npm install
npm run dev
```

---

## 🔗 API

Base URL:
```
http://localhost:8081/api/
```

Swagger UI:
```
http://localhost:8081/swagger-ui.html
```

---

## 🧩 Engineering Highlights

- Designed scalable REST APIs with filtering, pagination, and sorting  
- Implemented secure JWT-based authentication and protected routes  
- Used Redis for caching to improve performance of cart operations  
- Followed clean layered architecture for maintainability  
- Enabled containerized setup using Docker for reproducibility  

---

## 📊 Future Improvements

- Microservices architecture  
- Payment gateway integration  
- Real-time inventory updates  
- CI/CD pipeline  

---