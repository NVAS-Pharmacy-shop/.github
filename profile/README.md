# 💊 NVAS-Pharmacy-Shop

A full-stack pharmacy web application built with **Django**, **React (TypeScript)**
Designed with scalability, security, and real-time capabilities in mind.

---

## 🚀 Features

- 🔐 **Robust Security Mechanisms**
  - Role-Based Access Control (RBAC)
  - JWT Authentication
  - Password reset via email
  - OAuth2 integration (e.g., Google)
  - CAPTCHA protection on sensitive endpoints
  - Full encryption of sensitive user data

- 🗃️ **Concurrent Data Access**
  - Designed and tested strategies for concurrent database access
  - Implemented **optimistic** and **pessimistic** locking
  - Proof-of-concept simulations for future high-traffic scenarios

- 📦 **Real-Time Delivery Tracking**
  - RabbitMQ-based communication between main app and simulated delivery service
  - Live delivery location updates on the frontend via WebSockets

- 🐳 **Dockerized Infrastructure**
  - Full application containerized with **Docker**
  - Load balancing via **NGINX**
  - Horizontal scaling support for backend services

---
##  📐 Architecture Overview
![Application Architecture](https://github.com/user-attachments/assets/0ab33f6d-9fd0-435f-a481-896276528fcf)


## 🛠️ Tech Stack

**Backend:**
- Django & Django REST Framework
- PostgreSQL
- RabbitMQ

**Frontend:**
- React with TypeScript
- WebSocket integration

**Infrastructure:**
- Docker
- NGINX (as load balancer)

---

## 📁 Project Structure

