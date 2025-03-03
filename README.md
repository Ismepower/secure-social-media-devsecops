# secure-social-media-devsecops
My secure-social-media-devsecops Project

# Secure Social Media App Deployment with DevSecOps 🚀

## 📌 Project Overview  
This project demonstrates how to **securely deploy a social media application** on AWS using **DevSecOps best practices**.  
The pipeline integrates **Terraform, Jenkins/GitHub Actions, security tools (Snyk, SonarQube, Trivy, OWASP ZAP), and AWS security services**.

## 🏗️ Architecture & Tech Stack  
- **Cloud Provider**: AWS (EC2, S3, RDS, IAM, VPC)  
- **Infrastructure as Code (IaC)**: Terraform  
- **CI/CD Pipeline**: Jenkins / GitHub Actions  
- **Containerization**: Docker & Kubernetes  
- **Security Tools**:  
  - **Snyk** – Dependency scanning  
  - **SonarQube** – Static code analysis  
  - **Trivy** – Container vulnerability scanning  
  - **OWASP ZAP** – Dynamic security testing (DAST)  

---

## 🔧 Setup & Installation  

### **1️⃣ Infrastructure Setup (AWS & Terraform)**  
```bash
# Initialize Terraform
terraform init

# Deploy infrastructure
terraform apply -auto-approve

