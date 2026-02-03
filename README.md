# 👋 Hello, I'm Jiwan

Backend Engineer building and operating an **MSA-based social platform**.  
Focused on **service separation**, **authentication**, **real-time communication**, and **data consistency**.

I design backend systems with scalability and maintainability in mind,  
and enjoy structuring services that can grow into real-world products.

---

## 🌟 Core Project – Aniverse Platform

**Aniverse** is a microservice-based social platform built from the ground up.  
Each service is independently developed and deployed, following MSA principles.

### 🧩 Service Composition

- **Aniverse-common**  
  Shared domain models, common utilities, and core business logic used across services.

- **Aniverse-auth / user (included in common)**  
  Authentication, authorization, JWT-based login, and user management.

- **Aniverse-search**  
  Search service currently implemented with **PostgreSQL-based querying**,  
  designed with future migration to Elasticsearch in mind.

- **Aniverse-chat**  
  Real-time chat service using **WebSocket + STOMP**.

- **Aniverse-websocket**  
  WebSocket gateway handling real-time connections and session management.

- **Aniverse-noti**  
  Notification service for chat, system events, and user alerts.

- **Aniverse-front**  
  Frontend application built with **React + TypeScript**.

> Each service is designed to be loosely coupled and independently scalable.

---

## 🛠 Tech Stack

### Backend
- Java, Spring Boot
- Kotlin (partial services / experiments)
- PostgreSQL, Redis, MongoDB
- WebSocket, STOMP
- Kafka (event-based processing)

### Frontend
- React
- TypeScript

### Infra / DevOps
- Docker, Docker Compose
- Jenkins (CI/CD)
- NAS-based storage (media handling)

---

## 📂 Repository Overview

| Repository | Description |
|-----------|-------------|
| **Aniverse-common** | Core shared logic and domain modules |
| **Aniverse-front** | React-based frontend |
| **Aniverse-search** | PostgreSQL-based search service |
| **Aniverse-chat** | Real-time chat service |
| **Aniverse-websocket** | WebSocket connection service |
| **Aniverse-noti** | Notification service |
| **Aniverse-socialPlus / note / auction** | Experimental & side services |

---

## 📊 GitHub Stats

![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ynjw3758&layout=compact)

---

## 🎯 What I Value as a Developer

- Designing **clear service boundaries**
- Choosing **practical architectures**, not over-engineering
- Writing code that is **easy to maintain and extend**
- Thinking in terms of **real production scenarios**

---

## 📫 Contact & More

- GitHub: https://github.com/ynjw3758  
- Tech Blog: (to be added)

---

### 🔚 One-line Summary
> *“I don’t just build features — I design systems that can grow.”*
