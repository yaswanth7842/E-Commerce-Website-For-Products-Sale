# E-Commerce Microservices Application

This project is a full-stack **E-Commerce Web Application** built using **Microservices Architecture** with Spring Boot and React.

The application allows users to browse products, manage carts, add reviews, and manage delivery addresses. The system uses service discovery and an API Gateway to manage communication between multiple services.

---

## Architecture Overview

The project follows **Microservices Architecture** where each service is independently developed and deployed.

Main components:

- API Gateway
- Eureka Server (Service Discovery)
- Product Service
- Cart Service
- User Service
- Order Service
- Review Service
- Address Service

All services register with **Eureka Server**, and the **API Gateway** routes client requests to the appropriate service.

---

## Microservices Repositories

| Service | Repository |
|------|------|
| Eureka Server | https://github.com/yaswanth7842/eureka_service |
| API Gateway | https://github.com/yaswanth7842/API_Gateway |
| Product Service | https://github.com/yaswanth7842/Product_Service |
| Cart Service | https://github.com/yaswanth7842/Cart_Service |
| User Service | https://github.com/yaswanth7842/User_Service |
| Order Service | https://github.com/yaswanth7842/Order_Service |
| Review Service | https://github.com/yaswanth7842/Review_Service |
| Address Service | https://github.com/yaswanth7842/Address_Service |

---

## Tech Stack

### Backend
- Java
- Spring Boot
- Spring Cloud
- OpenFeign Client
- Eureka Service Registry
- API Gateway

### Frontend
- React.js
- Tailwind CSS

### Database
- MySQL

### Tools
- Eclipse IDE (Backend Development)
- VS Code (Frontend Development)
- Postman (API Testing)
- Git & GitHub

---

## Features

- Role-Based Authentication (Admin / User)
- Google OAuth2 Login
- Product Management (Admin only)
- Add to Cart functionality
- Product Reviews
- User Address Management
- Order Management
- Microservices communication using Feign Client
- Service Discovery using Eureka
- Centralized API routing using API Gateway

---

## Eureka Service Dashboard

All microservices are registered in **Eureka Server** for service discovery.

Example services running:

- API-GATEWAY
- PRODUCT-SERVICE
- CART-SERVICE
- USER-SERVICE
- ORDER-SERVICE
- REVIEW-SYSTEM
- ADDRESS-SERVICE

---

## How To Run The Project

1. Start **Eureka Server**
2. Start **API Gateway**
3. Start all Microservices:
   - Product Service
   - Cart Service
   - User Service
   - Order Service
   - Review Service
   - Address Service
4. Run the **React Frontend**
5. Access APIs through the **API Gateway**

---

## Author

Yaswanth  
Backend Developer | Java | Spring Boot | Microservices | React
