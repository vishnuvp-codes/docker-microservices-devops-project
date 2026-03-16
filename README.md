# Docker Microservices DevOps Project

## 📌 Project Overview
This project demonstrates a **containerized microservices architecture** using Docker and Docker Compose.  
It consists of multiple services including **Nginx, Node.js, Python, and MongoDB**, each running in separate containers.

The goal of this project is to understand **containerization, service orchestration, and microservices communication** in a DevOps environment.

---

## 🏗 Architecture

User Request  
↓  
Nginx (Reverse Proxy)  
↓  
Node.js Service  
↓  
Python Service  
↓  
MongoDB Database  

Nginx handles incoming requests and routes them to the backend services.

---

## ⚙️ Technologies Used

- Docker
- Docker Compose
- Nginx
- Node.js
- Python
- MongoDB
- Linux

---

## 📁 Project Structure
devops-microservices-project
│
├── docker-compose.yml
├── nginx/
│ └── nginx.conf
│
├── node-service/
│ ├── app.js
│ ├── package.json
│ └── Dockerfile
│
├── python-service/
│ ├── app.py
│ ├── requirements.txt
│ └── Dockerfile



### 2️⃣ Start all services


docker-compose up -d


---

### 3️⃣ Check running containers


docker ps


---

### 4️⃣ Access services

| Service | URL |
|------|------|
| Nginx | http://localhost |
| Node.js | http://localhost:3000 |
| Python | http://localhost:5000 |
| MongoDB | localhost:27017 |

---

## 🧠 Features

- Multi-container application using Docker Compose
- Microservices architecture
- Reverse proxy using Nginx
- Separate services for Node.js and Python
- MongoDB database container
- Container networking between services

---

## 📊 Skills Demonstrated

- Docker containerization
- Docker Compose orchestration
- Microservices architecture
- Reverse proxy configuration
- Backend service communication
- Database container management

---

## 🔮 Future Improvements

- Add CI/CD pipeline using GitHub Actions
- Implement monitoring with Prometheus and Grafana
- Deploy on cloud infrastructure (AWS / GCP)
- Add persistent storage for MongoDB
- Implement Kubernetes orchestration

---

## 👨‍💻 Author

Vishnu Priya

DevOps / Software Engineering Enthusiast

