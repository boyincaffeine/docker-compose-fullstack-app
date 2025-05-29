# Docker Compose Fullstack App 🐳

This project is a **cloned Node.js + MongoDB fullstack application** containerized using **Docker** and **Docker Compose**. The original source code was cloned from GitHub, and the **Dockerfile** and **docker-compose.yml** were written by me to containerize and orchestrate the application.

## 🔧 Tech Stack

- **Frontend**: (if applicable, e.g., React, EJS, etc.)
- **Backend**: Node.js / Express
- **Database**: MongoDB
- **Containerization**: Docker
- **Orchestration**: Docker Compose

## 📁 Project Structure

```bash
.
├── backend/                # Node.js app
│   ├── Dockerfile
│   └── ...
├── docker-compose.yml
└── README.md
🚀 Getting Started
Prerequisites
Docker

Docker Compose

Run the App
bash
Copy
Edit
docker-compose up --build
This command builds and starts all services defined in the docker-compose.yml file.

Access the App
Frontend: http://localhost:3000 (or your configured port)

MongoDB: Running in its own container on default port 27017

📦 Docker Overview
Dockerfile Highlights
Installs dependencies

Copies source code

Exposes application port

Uses multi-stage build if needed

docker-compose.yml Highlights
Defines app and mongo services

Uses named volumes for data persistence

Enables network communication between containers

🧠 Why Docker Compose?
Simplifies multi-container setups

Easy to scale or modify individual services

Ideal for local development and CI/CD

🛠️ Customization
The original app was cloned from GitHub

I wrote the Dockerfile and docker-compose.yml from scratch

Configured environment variables, ports, and volumes

