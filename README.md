## 🚀 Three-Tier Todo Application on Amazon EKS

A production-style Three-Tier Todo Application deployed on **Amazon Elastic Kubernetes Service (EKS)** using **Docker**, **Kubernetes**, **AWS Application Load Balancer**, and **Amazon ECR**.

This project demonstrates how a modern cloud-native application is containerized, deployed, scaled, and exposed on AWS using Kubernetes best practices.

---

## 📌 Project Overview

The application follows a **Three-Tier Architecture**:

- **Frontend** – React.js
- **Backend** – Node.js & Express.js REST API
- **Database** – MongoDB

Each component runs inside its own Docker container and is deployed independently on Kubernetes.

---

## 🏗️ Architecture


## 🛠️ Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- Docker
- Kubernetes
- Amazon EKS
- Amazon ECR
- AWS Load Balancer Controller
- YAML
- Terraform *(Infrastructure folder included for future IaC implementation)*

---
## 📂 Project Structure


three-tier-eks
│
├── app/
│ ├── frontend/
│ ├── backend/
│ └── mongodb/
│
├── k8s_manifests/
│
├── terraform/
│
└── README.md

---

## ⚙️ Deployment Workflow

1. Containerized frontend, backend and database using Docker.
2. Built Docker images.
3. Pushed images to Amazon ECR.
4. Created Kubernetes Deployments and Services.
5. Configured Ingress using AWS Load Balancer Controller.
6. Deployed application on Amazon EKS.
7. Verified communication between all three tiers.

---
## ✨ Features

- Three-Tier Architecture
- REST API
- CRUD Operations
- Kubernetes Deployments
- Kubernetes Services
- AWS Application Load Balancer
- Dockerized Microservices
- Highly Available Backend Pods
- Internal Service Communication

---
## 📸 Screenshots


## 📚 What I Learned

Through this project I gained hands-on experience with:

- Docker containerization
- Kubernetes Deployments
- Kubernetes Services
- Kubernetes Ingress
- AWS Elastic Kubernetes Service (EKS)
- Amazon Elastic Container Registry (ECR)
- AWS Load Balancer Controller
- Debugging production deployment issues
- Networking between application tiers

---

## 👩‍💻 Author

**Siddhi Ayare**
