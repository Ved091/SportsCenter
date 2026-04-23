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

## Application Flow:

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/cfbc1499-873f-45ec-a7ed-4cb4dcac8efe)

## Add To Cart:

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/44e21af9-82eb-46c5-84c8-33e2f0824073)

## Basket Page:

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/4f8853a2-a65c-418d-968e-3870392e277d)


![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/ca65abd2-c58b-480d-a4b8-9f4707a11df1)

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/568578a3-df7d-4aa8-93b7-0781e9ff0633)

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/094c8d92-0b20-4f11-85b4-a7b2a6c1e531)

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/9c83b0cf-1552-42e1-bdfd-b9354704e801)

![image](https://github.com/rahulsahay19/Blog-Images/assets/3886381/aea25748-d100-42f3-a9f9-3eae8b0a53e2)

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