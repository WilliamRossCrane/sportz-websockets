# ⚽ Sportz Websocket – Real-Time Broadcast Engine

![Project Status](https://img.shields.io/badge/status-finished-brightgreen)

This project is **finished** and was built as part of the JavaScript Mastery WebSockets Crash Course.

The goal of this project is to design and implement a **high-frequency real-time broadcast engine** capable of delivering live match scores, commentary, and ball-by-ball updates to **100,000+ concurrent users** with sub-second latency.

This build moves from core WebSocket theory to a production-ready architecture demonstrating how to scale real-time systems without overwhelming the server.

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![WebSockets](https://img.shields.io/badge/-WebSockets-000000?style=flat-square) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![Arcjet](https://img.shields.io/badge/-Arcjet-111111?style=flat-square) ![Site24x7](https://img.shields.io/badge/-Site24x7-FF6C00?style=flat-square)

---

## 📌 Project Overview

This project focuses on building a scalable real-time system that:

- Establishes and manages WebSocket connections
- Ingests match data via REST APIs
- Broadcasts live updates to thousands of connected clients
- Maintains low latency under high concurrency
- Implements production-grade monitoring and security

It simulates a live sports broadcasting platform where data is pushed instantly to connected users.

---

## 📌 Project Retrospective

- 📄 [View the Project Retrospective](./PROJECT_RETROSPECTIVE.md)

Outlines key technical learnings, challenges faced, and how this project maps to industry practices.

---

## ⚙️ Tech Stack

- **Node.js** – Backend runtime
- **Express** – REST API layer
- **WebSocket (ws)** – Real-time communication engine
- **MongoDB & Mongoose** – Data persistence and schema modeling
- **Arcjet** – Security and traffic protection
- **Site24x7** – Application performance monitoring

---

## 🔋 Features

👉 **WebSocket Server Architecture**  
Manages persistent connections, handles message events, and implements scalable broadcast patterns.

👉 **Matches REST API (CRUD)**  
Full Create, Read, Update, and Delete functionality for managing match data.

👉 **Live Commentary Streaming**  
Streams ball-by-ball commentary updates instantly to all connected clients.

👉 **Hybrid REST + WebSocket System**  
Uses REST APIs for secure data ingestion and WebSockets for real-time distribution.

👉 **Security with Arcjet**  
Implements traffic protection and abuse prevention to safeguard the broadcast engine.

👉 **Monitoring & Observability**  
Integrated with Site24x7 for performance tracking, uptime monitoring, and system insights.

👉 **Production Deployment**  
Configured for scalable deployment with database seeding and performance optimisation.

---

## 🧠 Architecture Goals

- Persistent WebSocket connections
- Efficient broadcast patterns
- Fault tolerance
- Sub-second update latency
- Separation of ingestion (REST) and distribution (WebSocket)

---

## 🤸 Quick Start

### ✅ Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### 📦 Install Dependencies

npm install

### 🔐 Set Up Environment Variables

Create a .env file in the root of your project and add the following:

- DATABASE_URL="YOUR_DATABASE_KEY"
- PORT=8000
- HOST=0.0.0.0

- ARCJET_KEY="YOUR_ARCJET_KEY"
- ARCJET_ENV="development"

- API_URL="http://localhost:8000"
- API_URL="YOUR_REAL_PRODUCTION_URL"

### 🚀 Run the Project Locally

npm run dev

Then, open your browser and go to http://localhost:8000 to see the app in action.

---

## 📺 Course Link

This project was built using the [JavaScript Mastery Next.js 16 Crash Course](https://jsmastery.pro/).

Watch the full tutorial on YouTube:  
🔗 [Build a Full Stack Dev Events Platform with Next.js 16 (YouTube)](https://www.youtube.com/watch?v=pbOXOY78dNA&t=517s)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub and joining the JSMastery community:

- [JS Mastery Discord](https://discord.gg/jsmastery)
- [JS Mastery Pro](https://jsm.dev/uber-jsmpro)
- [More Projects](https://jsm.dev/uber-kit)
