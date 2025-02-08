# Microservices E-Commerce Project

- This is a scalable and containerized E-commerce application built using Go
(Golang), designed with microservices architecture and deployed on AWS
EKS (Elastic Kubernetes Service).
- The project is automated using a CI/CD pipeline with Jenkins and the
services are containerized using Docker.

## Tech Stack:

- Backend: Golang (Go)
- API Gateway: Nginx
- Database: MySQL
- Containerization: Docker
- Orchestration: Kubernetes (AWS EKS)
- CI/CD Pipeline: Jenkins

## CI/CD Pipeline using Jenkins:

- Code Commit: Developers push code to GitHub/GitLab.
- Jenkins Build Trigger: Jenkins detects changes and triggers the pipeline.
- Build & Test:
- Golang unit tests
- Build Docker images
- Push to Docker Registry: Images are pushed to Amazon ECR/DockerHub.
- Deploy to EKS: Kubernetes applies updated deployments.          
