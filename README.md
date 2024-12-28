# Web Application Deployment Pipeline with Jenkins, Ansible, and Docker

## Overview
An automated CI/CD pipeline that deploys a 3-tier web application (React frontend, Node.js backend, PostgreSQL database) using Jenkins, Ansible, and Docker on AWS infrastructure.

## Key Features
- Fully automated deployment process
- Containerized microservices architecture  
- Infrastructure as Code using Terraform
- Container orchestration with Ansible
- Automated image management with AWS ECR
- High availability and scalability

## Technologies
- **Infrastructure:** AWS, Terraform
- **CI/CD:** Jenkins Pipeline
- **Configuration Management:** Ansible 
- **Containerization:** Docker
- **Application Stack:** React, Node.js, PostgreSQL

## Architecture

The application consists of three containerized services:
- Frontend (React) - Port 3000
- Backend (Node.js) - Port 5000  
- Database (PostgreSQL) - Port 5432

## Quick Start

### Prerequisites
- AWS Account
- Jenkins Server with required plugins
- Terraform and Ansible installed

### Deployment
1. Clone the repository
2. Configure AWS credentials
3. Run Jenkins pipeline 
4. Access the application at `http://<react-instance-ip>:3000`

## Results
A production-ready web application with:
- Automated infrastructure provisioning
- Containerized microservices
- Continuous Integration/Deployment
- Scalable architecture