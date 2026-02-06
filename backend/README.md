# 🚀 DevOps CI/CD Project – Dockerized Django Backend

This project demonstrates a real-world DevOps workflow by containerizing a Django backend application using Docker and resolving production-level configuration issues.

## 🔧 Tech Stack
- Python 3.10
- Django 4.2 (LTS)
- Docker & Dockerfile
- Git & GitHub
- Linux

## 📌 Project Features
- Django backend application
- Dockerized environment for consistent deployment
- Fixed Python–Django version compatibility issues
- Resolved Django ROOT_URLCONF and settings configuration
- Ready for CI/CD pipeline integration

## 🏗️ Project Architecture
User → Browser → Docker Container → Django Backend

## ▶️ How to Run the Project
```bash
docker build -t django-backend .
docker run -p 8000:8000 django-backend