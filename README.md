# 🐳 Node.js Dockerized Application

This is a simple **Node.js** application containerized using **Docker**. The app allows users to **insert** and **fetch** data on their local mahine by creating and runnig the **Container**.

## 🚀 Features

- Built using **Node.js**.
- Containerized with **Docker**
- Stores and fetches user data
- Easy to set up and run on any machine
- Built a **mongodb** database and setup with the help of **Docker** for our application.
- By using the **Docker container** technique we can use the **mongodb** database

---

## 🛠️ Technologies Used

- **Node.js** - Backend framework
- **Docker** - Containerization
- **MongoDB / JSON / Any Storage** (depending on your setup)
- **MongoExpress** - User interface for mongoDB
- **Docker Volumes** - For presistent data storage for containers.

---

## 📂 Project Structure

```bash
├── Dockerfile
├── docker-compose.yml   # If used
├── package.json
├── server.js            # Main app/server file
├── routes/              # API routes
├── models/              # Database models
├── public/              # Static files (if any)
└── README.md
```
## ⚙️ Installation & Setup
- Clone the Repository
```bash
  git clone https://github.com/adarshkrsingh07/Developing_with_Docker.git
  ```
- Navigate to the directory
```bash
   cd <dir_name>
```
- Run the Container
```bash
  docker compose -f mongodb.yaml up -d
```
- Start your Server
```bash
  node server.js
```
- Access the Application

Node.js App: http://localhost:5050

Mongo Express: http://localhost:8081

