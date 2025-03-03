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
![Screenshot (13)](https://github.com/user-attachments/assets/36b68928-2d9b-4583-8565-3650b7cfbe57)
![Screenshot (14)](https://github.com/user-attachments/assets/a7b98492-c708-445b-a692-8be0523bbf7c)
![Screenshot (15)](https://github.com/user-attachments/assets/2f0e5aa0-16c9-4175-aa0e-cafc0b32c687)
![Screenshot (16)](https://github.com/user-attachments/assets/6d74324d-5fa8-4d38-b860-e63f998257f7)
![Screenshot (17)](https://github.com/user-attachments/assets/a96b2248-c089-46be-9ce6-e99dbc883987)
