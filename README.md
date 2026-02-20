# End to End CI/CD Pipeline for Containerized Java Application on AWS EKS using Terraform, Docker and Kubernete
This project implements a complete DevOps based CI/CD pipeline for deploying a containerized Java web application into an AWS EKS Kubernetes cluster using Infrastructure as Code.
The pipeline automates the entire process from application code checkout to production deployment including:
- Infrastructure provisioning using Terraform
- Application build using Maven
- Code Quality Analysis using SonarQube
- Security vulnerability scan using OWASP Dependency Check
- Container image build using Docker
- Image security scan using Trivy
- Artifact storage in AWS S3
- Container image push to DockerHub
- Application deployment on AWS EKS using Kubernetes manifests
-----
# Architecture Flow
Developer Code → Jenkins Pipeline → SonarQube Analysis → OWASP Scan → Maven Build → Docker Image Build → Trivy Scan → DockerHub Push → Kubernetes Deployment on AWS EKS

---
# Tech Stack Used
- Java
- Maven
- Docker
- Docker Compose
- Kubernetes
- Terraform
- AWS EKS
- Jenkins
- SonarQube
- OWASP Dependency Check
- Trivy
- MySQL
- AWS S3
---
# Infrastructure Provisioning using Terraform
Terraform is used to provision the AWS EKS cluster.
Cluster Provisioning Steps
terraform init
terraform validate
terraform plan
terraform apply --auto-approve

---
# Key Outcomes
- Automated infrastructure provisioning using Terraform
- Containerized Java application deployment
- Integrated CI/CD pipeline using Jenkins
- Code Quality and Security Scanning
- Secure Docker Image Deployment
- Scalable deployment using AWS EKS Kubernetes Cluster
