# # EKS Nginx Deployment Project

## Overview
This project demonstrates how to deploy a containerized Nginx application on AWS EKS using Kubernetes.

It simulates a production-like DevOps environment with deployment automation and scalable infrastructure.

## Tech Stack
- AWS EKS
- Kubernetes
- Docker
- Nginx

## Architecture
- Kubernetes Deployment for Nginx
- Kubernetes Service for external access
- Containerized application running on EKS cluster

## Deployment Steps
1. Create EKS cluster
2. Configure kubectl
3. Apply deployment:
   kubectl apply -f nginx-deployment.yaml
4. Expose service:
   kubectl apply -f nginx-service.yaml

## Outcome
- Successfully deployed a scalable Nginx application on Kubernetes
- Demonstrated container orchestration and cloud deployment skills
- Simulated real-world DevOps deployment workflow

## Author
Komlavi Gidieks-nginx-project
