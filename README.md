# SWT Milefiz – Multiplayer Board Game (Web)

SWT Milefiz is a multiplayer, web-based board game inspired by the classic game  
**“Malefiz”**.

The project was developed as part of a software engineering project and focuses on
clean architecture, real-time communication, and collaborative development.

The application consists of:

- a **Spring Boot backend** handling game logic and real-time communication
- a **modern web frontend** for interactive gameplay

---

## Tech Stack

### Backend

- Java 21
- Spring Boot
- WebSockets (real-time game state updates)
- Gradle

### Frontend

- Node.js
- Vite
- Vue3
- Three.js
- JavaScript / TypeScript
- HTML / CSS

---

## Architecture Overview

- Backend and frontend are **strictly decoupled**
- Real-time multiplayer communication via **WebSockets**
- Game state and rules are managed server-side
- Frontend consumes REST APIs and WebSocket events

---

## Local Development

### Prerequisites

- Java 21
- Node.js (>= 18)
- npm

---

### Backend

From the project root:

```bash
./gradlew.bat bootRun
```

---

### Frontend

In a separate terminal:

```bash
cd frontend
npm install
npm run dev
```

---

## Project Context

This project was developed in a **team environment** using:

- Scrum methodology
- iterative development cycles
- collaborative version control and code reviews

Special attention was given to:

- clean separation of concerns
- maintainability
- cross-platform compatibility (Linux / Windows)

---

## Screenshots / Poster

A detailed project poster was created to visualize:

- system architecture
- gameplay concept
- technical decisions

📄 **Project Poster:**  
[View SWT Milefiz Poster](docs/SWTPro_MIlefiz_Poster.pdf)

---

## Author

**Houssam Sakah**  
Software Engineering / Media Informatics
