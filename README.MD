# 🚀 DevSecOps CI/CD Pipeline on AWS EC2 with Jenkins, SonarQube, Trivy & Docker

## 📌 Project Overview

This project demonstrates an end-to-end **DevSecOps CI/CD Pipeline** built on an **AWS EC2 Ubuntu instance**. The pipeline automates application build, security scanning, Docker image creation, image publishing to Docker Hub, and application deployment.

Security is integrated throughout the CI/CD lifecycle using **SonarQube** for static code analysis and **Trivy** for vulnerability scanning before deployment.

---

# 🏗️ Project Architecture

<p align="center">
    <img src="./images/project-architecture.png" width="100%" alt="Project Architecture">
</p>

---

# ☁️ AWS EC2 Instance

The complete DevSecOps environment is hosted on an Ubuntu EC2 instance.

<p align="center">
    <img src="./images/instance.png" width="100%" alt="EC2 Instance">
</p>

---

# 🔓 Required Ports

<p align="center">
    <img src="./images/requireed-ports.png" width="100%" alt="Required Ports">
</p>

---

# ⚙️ CI/CD Pipeline Workflow

Pipeline Stages

<p align="center">
    <img src="./images/cicd.png" width="100%" alt="CI/CD Pipeline">
</p>

---

# 🔨 Jenkins webhook

Jenkins automates the complete CI/CD process using declarative pipelines.

<p align="center">
    <img src="./images/jenkins-web-hook.png" width="100%" alt="Jenkins Dashboard">
</p>

---

# 🗄️ Database

Application data is stored in the backend database.


<p align="center">
    <img src="./images/database.png" width="100%" alt="Database">
</p>

---

# 🐳 Docker Hub Repository

After successful security scans, Docker images are automatically pushed to Docker Hub.

<p align="center">
    <img src="./images/dockerhub.png" width="100%" alt="Docker Hub">
</p>

---

# 📦 Docker Images

Docker images generated during the pipeline.

<p align="center">
    <img src="./images/docker-images.png" width="100%" alt="Docker Images">
</p>

---

# 🔍 SonarQube Analysis

Static code analysis is performed before deployment.

<p align="center">
    <img src="./images/sonar.png" width="100%" alt="SonarQube">
</p>

---

# ✅ Application Testing

Successful application execution after deployment.


<p align="center">
    <img src="./images/test-ui.png" width="100%" alt="Application Testing">
</p>

---

# 🛡️ Trivy Security Scan

Trivy performs vulnerability scanning for both the file system and Docker images.

<p align="center">
    <img src="./images/trivy.png" width="100%" alt="Trivy">
</p>

---

# 🌐 Application UI

Final deployed application running inside a Docker container.

<p align="center">
    <img src="./images/App-ui.png" width="100%" alt="Application UI">
</p>

---


# 🔄 Complete Pipeline Flow

```
Developer
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline
      │
      ▼
Build Application
      │
      ▼
SonarQube Analysis
      │
      ▼
Quality Gate
      │
      ▼
Trivy File Scan
      │
      ▼
Docker Build
      │
      ▼
Trivy Image Scan
      │
      ▼
Docker Hub
      │
      ▼
Docker Deployment
      │
      ▼
Application
      │
      ▼
Database
      │
      ▼
Users
```

---

# 📈 Key Features

- End-to-End CI/CD Automation
- DevSecOps Implementation
- Static Code Analysis
- Vulnerability Scanning
- Docker Containerization
- Automated Image Deployment
- Docker Hub Integration
- Continuous Delivery
- Secure Application Deployment

---

# 👨‍💻 Author

**Yogesh Ingavale**

Cloud & DevOps Engineer
