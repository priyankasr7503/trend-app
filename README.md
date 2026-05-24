# Trendify App Deployment

This project demonstrates containerization and deployment of a frontend application using Docker and Kubernetes.

## Technologies Used
- HTML/CSS/JavaScript
- Docker
- Docker Hub
- Kubernetes
- GitHub

## Steps Performed
1. Built Docker image
2. Created Docker Hub repository
3. Pushed Docker image to Docker Hub
4. Created Kubernetes deployment
5. Created Kubernetes service
6. Verified pods and services
7. Accessed application on localhost

## Docker Image
trend-app

## Kubernetes Commands Used

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services
