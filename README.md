# 🖥️ EC2-based Nginx Web Server with Application Load Balancer - AWS Hands-on Project

This project demonstrates how to deploy a simple web server on EC2 instances behind an AWS Application Load Balancer (ALB). The solution ensures high availability and basic load distribution across multiple servers.

---

## ✅ Project Features

Two EC2 instances running:

- **Apache Web Server** (Instance 1)
- **Nginx Web Server** (Instance 2)

Application Load Balancer (ALB) configured with:

- Health checks
- Round-robin traffic distribution
- Security Groups for controlled access (SSH & HTTP)
- Manual scaling demonstration

Tested in **eu-north-1** AWS region

---

## 🛠️ Tools & Technologies

- Amazon EC2
- Amazon VPC
- Amazon Application Load Balancer
- Security Groups
- Apache & Nginx
- AWS Management Console

---

## 🌐 Outcome

Accessing the Load Balancer DNS shows different pages on refresh, proving traffic is distributed between two EC2 instances:

**Example outputs:**

