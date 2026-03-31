# Advanced CI/CD DevOps Project

## Features
- Flask App
- Docker Containerization
- GitHub Actions CI/CD
- Kubernetes Deployment

## Steps
1. Build Docker Image
2. Push to Docker Hub
3. Deploy using Kubernetes

## Run Locally
docker build -t cicd-app .
docker run -p 5000:5000 cicd-app

## Kubernetes
kubectl apply -f k8s/
