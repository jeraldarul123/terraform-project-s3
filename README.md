# terraform-project-s3
# 🌍 Personal Portfolio - Hosted on AWS S3 using Terraform 🚀

## Overview

This project is my **personal portfolio website**, hosted on **AWS S3** using **Terraform** for Infrastructure as Code (IaC). It enables automated, scalable, and cost-effective static website hosting.

## 🛠️ Tech Stack

- **AWS S3** – Static website hosting
- **Terraform** – Infrastructure as Code
- **Route 53** – (Optional) Custom domain setup
- **CloudFront** – (Optional) CDN for performance & HTTPS

## 📌 Features

✅ Automated infrastructure deployment with Terraform  
✅ Scalable and cost-efficient hosting solution  
✅ Version-controlled and easily replicable setup  
✅ (Optional) HTTPS with AWS CloudFront & ACM  

## 🚀 Deployment Guide

### 1️⃣ Prerequisites
Ensure you have the following installed:
- [ ] Terraform
- [ ] AWS CLI (configured with credentials)
- [ ] A registered domain (if using Route 53)

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git  
cd YOUR_REPO_NAME  
```

### 3️⃣ Initialize Terraform
```bash
terraform init  
```

### 4️⃣ Preview the Infrastructure Changes
```bash
terraform plan  
```

### 5️⃣ Deploy the Infrastructure
```bash
terraform apply -auto-approve  
```

### 6️⃣ Access Your Portfolio
Once deployed, visit **S3 static website URL** or your custom domain.

## 🌍 Configuration Details

- **S3 Bucket Name:** `your-bucket-name`
- **Terraform State Storage:** `local` or `remote (S3 backend)`

## 🧹 Cleanup
To destroy resources when no longer needed:
```bash
terraform destroy -auto-approve  
```

## 🚀 Connect with Me
📩 www.linkedin.com/in/jeraldarul

