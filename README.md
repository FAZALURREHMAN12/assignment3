# Assignment 3: Kubernetes Orchestration & Full DevOps Pipeline

## Overview
A 3-tier microservice application deployed using Docker and Kubernetes on Minikube.

## Architecture
- **Nginx** — Reverse proxy (NodePort 30080)
- **Flask API** — Python REST backend (port 5000)
- **MySQL** — Relational database (port 3306)

## Quick Start
```bash
./start.sh
```

## Branching Strategy
- `main` — stable, final code
- `develop` — integration branch
- `feature/docker-setup` — Docker containerization
- `feature/k8s-deployment` — Kubernetes manifests
