# Cloud-Native Boutique

A production-style **7-service cloud-native e-commerce application** deployed on AWS using Kubernetes, Terraform, GitHub Actions, and Argo CD.

This project demonstrates an end-to-end DevOps workflow covering infrastructure provisioning, containerization, CI/CD, GitOps-based deployment, security, and Kubernetes observability.

---

## Project Overview

Cloud-Native Boutique is a microservices-based application designed to demonstrate how a modern cloud-native system can be built, containerized, deployed, and operated on AWS.

The project covers the complete deployment lifecycle:

```text
Developer
    ↓
GitHub
    ↓
GitHub Actions
    ↓
Docker Build
    ↓
Amazon ECR
    ↓
Argo CD
    ↓
AWS EKS
    ↓
Kubernetes Workloads
    ↓
Prometheus + Grafana

```

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Application | React, Node.js, PostgreSQL |
| Containers | Docker, Docker Compose |
| Orchestration | Kubernetes (AWS EKS) |
| Infrastructure | Terraform |
| CI/CD | GitHub Actions |
| GitOps | ArgoCD + Kustomize |
| Monitoring | Prometheus + Grafana |

