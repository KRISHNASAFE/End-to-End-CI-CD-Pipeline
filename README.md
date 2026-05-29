# End-to-End CI/CD Pipeline with Jenkins (DevSecOps Project)

# Overview

This project demonstrates a complete **End-to-End CI/CD pipeline** using Jenkins to automate build, test, security scanning, containerization, and deployment of a web application.

The pipeline follows modern **DevSecOps practices**, integrating code quality checks, container security scanning, and SBOM generation.

The pipeline automates:

- Code checkout
- Build & dependency installation
- Static code analysis
- Docker image creation
- Vulnerability scanning
- SBOM generation
- K8S deployment

---

# Architecture













# Tech Stack

- Jenkins (CI/CD Orchestration)
- GitHub (Source Control)
- Docker (Containerization)
- SonarQube (Code Quality Analysis)
- Trivy (Security Scanning)
- Syft / SBOM Generator
- Linux (Jenkins Host)
- Kubernetes (Deployment to Cluster)
---

# CI/CD Pipeline Stages

### 1. Code Checkout
- Pulls latest code from GitHub repository

### 2. Build Stage
- Installs dependencies
- Builds application

### 3. Code Quality Analysis
- SonarQube performs static code analysis
- Detects bugs, vulnerabilities, and code smells

### 4. Docker Build
- Creates Docker image for application

### 5. Security Scan
- Trivy scans Docker image for vulnerabilities

### 6. SBOM Generation
- Generates Software Bill of Materials for supply chain security

### 7. Push to Registry
- Docker image pushed to DockerHub / registry

### 8. Deployment
- Application deployed to K8S Cluster.

---

# Security Practices (DevSecOps)

- Credentials managed via Jenkins Credentials Store
- Secrets not exposed in pipeline logs
- Vulnerability scanning using Trivy
- SBOM generation for supply chain transparency

---

# Key Features

- Fully automated CI/CD pipeline
- Integrated security scanning (DevSecOps)
- Code quality enforcement using SonarQube
- Containerized deployment using Docker
- Multibranch pipeline support
- Production-ready workflow
- Multi-stage Jenkins pipeline
---

# Clone Repository

- git clone https://github.com/your-username/your-repo.git
- cd your-repo

---

# Run Jenkins Pipeline

- Create Jenkins Pipeline Job
- Connect GitHub repository
- Configure credentials
- Run pipeline

---

# Screenshots (To Add)

- Jenkins pipeline success
- SonarQube dashboard
- Docker image build logs
- Trivy scan results
- Running application

---

# Future Improvements

- Kubernetes deployment (EKS / Minikube)
- Prometheus + Grafana monitoring
- Automated rollback strategy
- Slack/Email notifications
- Blue-Green deployment strategy

---

# Author

Chirag G  
DevSecOps | Cloud | CI/CD Enthusiast




