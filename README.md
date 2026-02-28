# 🎨 PixCraft – Online Photo Editing Hub

PixCraft is a modern, browser-based photo editing platform designed to make creative image enhancement accessible, lightweight, and scalable.  

Built using modern web technologies and DevOps best practices, PixCraft combines real-time image editing with a fully automated CI/CD pipeline and cloud deployment architecture.

---

## 🚀 Features

- 📤 Image Upload & Editing
- ✂️ Crop, Resize, Rotate
- 🎚️ Brightness, Contrast, Grayscale, Blur Filters
- 🤖 AI-Based Image Enhancement
- 🖼️ Real-Time Filter Preview
- 📥 Export & Download Edited Images
- 📊 Monitoring & Logging Integration
- 🔁 Fully Automated CI/CD Pipeline

---

## 🏗️ Tech Stack

### Frontend
- React
- TypeScript
- Vite
- HTML5 Canvas
- CSS

### DevOps & Cloud
- Docker (Containerization)
- Kubernetes (Orchestration - scalable architecture)
- CircleCI (CI/CD Automation)
- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- AWS EC2 (Cloud Hosting)
- Prometheus & Grafana (Monitoring & Observability)
- Trivy (Security Scanning)

---

## 🧩 System Architecture

PixCraft follows a modern DevOps architecture:

1. **Version Control Layer**
   - Git + GitHub
   - Feature branching workflow

2. **CI/CD Automation Layer**
   - CircleCI pipeline triggers on every commit
   - Build → Test → Security Scan → Deploy

3. **Containerization Layer**
   - Dockerized frontend and backend services
   - Docker Compose for local orchestration

4. **Orchestration Layer**
   - Kubernetes-based scalable deployment
   - Rolling updates and self-healing pods

5. **Infrastructure Layer**
   - Terraform provisions AWS EC2 instances
   - Ansible configures runtime environments

6. **Monitoring Layer**
   - Prometheus collects metrics
   - Grafana dashboards visualize performance

---

## 🔄 CI/CD Pipeline Flow

1. Code pushed to GitHub
2. CircleCI triggers automated pipeline
3. Docker images built
4. Security scan via Trivy
5. Images pushed to Docker Hub
6. Deployment to AWS EC2 / Kubernetes
7. Monitoring begins automatically

If tests fail → deployment stops.

---

## 📊 Monitoring & Observability

- CPU & Memory Usage Tracking
- API Response Time Monitoring
- Container Health Checks
- Real-Time Dashboards (Grafana)
- Alerting for system anomalies

---

## 🔐 Security Implementation

- IAM Role-based Access
- Kubernetes Secrets
- Encrypted credentials
- SSH key-based authentication
- Automated vulnerability scanning

---

## 🧪 Testing Strategy

- Unit Testing (Image processing modules)
- Integration Testing (Frontend + Backend)
- End-to-End Testing (User workflow)
- Load Testing under concurrent usage
- CI/CD Automated Test Execution

---

## 🎯 Problem Solved

Most photo editing platforms are either:
- Overcomplicated
- Resource-heavy
- Require installation
- Lack deployment automation

PixCraft provides:
- Lightweight browser-based editing
- No installation required
- Unified editing experience
- Automated DevOps pipeline
- Scalable cloud deployment

---

## 📈 Future Enhancements

- AI-powered advanced filters
- Cloud-based image storage
- User authentication & profile system
- Collaborative editing features
- Full Kubernetes production deployment

---

## 👨‍💻 Authors

Vedant Agrawal  
Srishti Panda  

B.Tech CSE – Software Engineering  
SRM Institute of Science and Technology  

---

## 📌 Keywords

Photo Editing · DevOps · CI/CD · Docker · Kubernetes · AWS · Terraform · Ansible · Monitoring · Cloud Native · React · TypeScript

---

## ⭐ Project Highlights

✔ Full DevOps pipeline implementation  
✔ Infrastructure as Code  
✔ Security integrated into CI/CD  
✔ Cloud-native architecture  
✔ Real-time image editing experience  

---
