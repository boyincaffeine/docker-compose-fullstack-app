# 🚀 Docker Compose Crash Course App

This is a simple full-stack app built as part of a **Docker Compose crash course**. It demonstrates how to run a Node.js web app with a MongoDB backend using Docker Compose.

![Docker Compose Screenshot](./images/docker-compose-output.png)

## 🧩 Tech Stack

- 🌐 Node.js (Express server)
- 🗄️ MongoDB (with Mongo Express GUI)
- 🐳 Docker & Docker Compose

---

## 📸 Screenshots

### ✅ App Interface (localhost:3000)
![App Screenshot](./images/web-app.png)

### ✅ Mongo Express Dashboard (localhost:8081)
![Mongo Express](./images/mongo-express.png)

### ✅ Docker Compose Output
![Terminal Output](./images/docker-compose-output.png)

---

## 📁 Folder Structure

```bash
.
├── docker-compose.yml
├── my-app/
│   ├── Dockerfile
│   ├── package.json
│   └── index.html
🔧 How to Run
Clone the Repo

bash
Copy
Edit
git clone https://github.com/your-username/docker-compose-crash-course.git
cd docker-compose-crash-course
Run Docker Compose

bash
Copy
Edit
docker-compose up --build
Access the App

Web App: http://localhost:3000

Mongo Express: http://localhost:8081

🧠 Key Learning Highlights
Inter-service communication via Docker networks

Using environment variables for MongoDB configuration

Managing MongoDB visually with Mongo Express

Binding host and container ports

Static + dynamic content rendering from MongoDB

🔐 Environment Variables Used
yaml
Copy
Edit
# For MongoDB
MONGO_INITDB_ROOT_USERNAME: admin
MONGO_INITDB_ROOT_PASSWORD: admin1

# For App
MONGO_DB_USERNAME: admin
MONGO_DB_PWD: pass

# For Mongo Express
ME_CONFIG_MONGODB_SERVER: mongodb
ME_CONFIG_MONGODB_ADMINUSERNAME: admin
ME_CONFIG_MONGODB_ADMINPASSWORD: admin1
🥂 Special Thanks
Thanks to the open-source community for the amazing base images and tutorials!

