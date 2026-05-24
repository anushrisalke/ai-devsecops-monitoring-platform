# AI-Powered DevSecOps Monitoring & Automated Deployment Platform

## Overview

This project is a cloud-native DevSecOps platform that automates backend deployment using Docker, Terraform, AWS EC2, and GitHub Actions CI/CD workflows.

The platform also integrates Trivy vulnerability scanning to improve container security during the deployment pipeline.

---

## Features

- Dockerized Node.js backend
- Infrastructure provisioning using Terraform
- AWS EC2 deployment
- GitHub Actions CI/CD pipeline
- Automated vulnerability scanning with Trivy
- Public cloud deployment
- Health monitoring API endpoint

---

## Tech Stack

| Category | Technologies |
|---|---|
| Backend | Node.js, Express |
| Containerization | Docker |
| CI/CD | GitHub Actions |
| Security | Trivy |
| Cloud | AWS EC2 |
| Infrastructure as Code | Terraform |
| Version Control | Git & GitHub |

---

## Architecture

GitHub → GitHub Actions → Docker → Terraform → AWS EC2 → Backend API

---

## CI/CD Workflow

1. Push code to GitHub
2. GitHub Actions pipeline triggers
3. Backend dependencies install automatically
4. Docker image builds
5. Trivy security scan runs
6. Deployment workflow validates infrastructure

---

## API Endpoint

```bash
GET /health

### Sample Response

```json
{
  "status": "OK",
  "message": "AI DevSecOps Platform Backend Running"
}
```

---

## Learning Outcomes

- Docker containerization
- Infrastructure as Code using Terraform
- AWS EC2 deployment
- SSH-based cloud access
- GitHub Actions CI/CD
- DevSecOps security scanning
- Linux server management

---

## Future Improvements

- Prometheus & Grafana monitoring
- Kubernetes deployment
- Nginx reverse proxy
- HTTPS SSL setup
- Automated deployment to EC2