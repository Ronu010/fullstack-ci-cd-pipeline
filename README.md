# 🚀 Fullstack DevOps CI/CD Pipeline

This project demonstrates a complete DevOps pipeline for a full-stack application using **Docker**, **Jenkins**, **Terraform**, and **Kubernetes**.

---

## 📦 Tech Stack

- **Frontend**: Static HTML (Dockerized)
- **Backend**: Node.js + Express API
- **CI/CD**: Jenkins + GitHub
- **Containerization**: Docker + Docker Compose
- **Orchestration**: Kubernetes (Minikube/EKS)
- **Infrastructure as Code**: Terraform (AWS)

---

## 🔧 Features

- ✅ Multi-stage Jenkins pipeline: `Build → Test → Dockerize → Push → Deploy`
- ✅ Docker Compose setup for local development
- ✅ Kubernetes deployment manifests
- ✅ Terraform scripts for AWS infrastructure provisioning

---

## 📁 Project Structure

fullstack-devops-ci-cd/
├── backend/ # Node.js backend
├── frontend/ # Static frontend (HTML)
├── jenkins/ # Jenkinsfile for pipeline
├── terraform/ # Terraform AWS setup
├── docker-compose.yml # Dev environment
└── README.md


## 🚀 How to Run Locally


# Clone the repo
git clone https://github.com/<your-username>/fullstack-devops-ci-cd.git
cd fullstack-devops-ci-cd

# Start the app using Docker Compose
docker-compose up --build
🌐 Frontend: http://localhost:8080

📡 Backend API: http://localhost:5000/api







