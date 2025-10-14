# Node TODO App — CI/CD with Jenkins & Docker

A simple **Node.js TODO web app** with a complete **CI/CD pipeline** using **Jenkins**, **Docker**, and **Docker Hub**.

---

## 🚀 Features
- Node.js + Express.js backend  
- Dockerized application  
- Jenkins pipeline for:
  - Cloning code from GitHub  
  - Building and pushing Docker image to Docker Hub  
  - Deploying via Docker Compose  

---

## ⚙️ Setup

### Build and Run Locally
```bash
docker build -t node-app-test-new .
docker run -d -p 8000:8000 node-app-test-new
Or with Docker Compose
docker-compose up -d


### App runs at http://localhost:8000
```bash
🧾 Jenkins Pipeline Stages .

Clone Code – Pulls repo from GitHub

Build – Builds Docker image

Push – Pushes image to Docker Hub

Deploy – Runs updated container

###👤 Author
```bash
Vivek Choudhary .
