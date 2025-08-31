# AWS-Grade-3-Tier-Architecture

## 📌 Overview
This project demonstrates a **3-Tier Web Application** deployed on **Amazon Web Services (AWS)** using best practices for scalability, security, and high availability.

The architecture consists of:
- **Presentation Tier (Frontend)** – React web application hosted on S3 + CloudFront
- **Application Tier (Backend)** – Node.js/Express js running on EC2 or AWS Elastic Beanstalk
- **Database Tier** – Amazon RDS (MySQL/PostgreSQL)

---

## 🏗️ Architecture Diagram
*(draw.io / Lucidchart / Excalidraw export)*

---

## 🚀 Services Used
- Amazon VPC (with Public & Private Subnets)
- Internet Gateway & NAT Gateway
- Application Load Balancer (ALB)
- Auto Scaling Groups
- Amazon S3 + CloudFront (static hosting & CDN)
- Amazon RDS (MySQL/PostgreSQL)
- AWS IAM (roles & permissions)
- AWS CloudWatch (monitoring & alerts)

---

## 📂 Project Structure
