# NGINX Deployment on Kubernetes (Minikube)

This project demonstrates deploying an NGINX application on a local Kubernetes cluster using Minikube.

## What I did
- Created a Kubernetes Deployment for NGINX
- Used a ConfigMap to serve custom HTML content
- Exposed the application using a NodePort Service
- Deployed and tested the application on Minikube

## Tech Used
- Kubernetes
- Minikube
- Docker
- NGINX

## How to Run
```bash
minikube start
kubectl apply -f k8s/
minikube service nginx-service
