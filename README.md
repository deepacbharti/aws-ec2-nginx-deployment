# aws-ec2-nginx-deployment
Hosted a premium cloud portfolio website on AWS EC2 using Linux + Nginx


# 🚀 AWS EC2 Nginx Deployment — Live Cloud Portfolio

This project hosts my personal Cloud & DevOps portfolio on an Amazon Linux EC2 instance using Nginx Web Server.

🔗 **Live Website:** http://13.233.25.92/  
🧑‍💻 **Author:** Deepak Bharti  
🎯 **Goal:** Cloud / DevOps Internship

---

## 📌 Technologies Used
- AWS EC2 (Compute)
- Linux System Administration
- Nginx Web Server
- SSH Secure Access
- Security Groups (Firewall Rules)
- Git & GitHub

---

## 🏗️ Project Architecture

User → Internet → AWS EC2 → Linux → Nginx → Portfolio Website

---

## 📍 Key Achievements

| Feature | Status |
|--------|--------|
| EC2 instance launched (Free Tier) | ✔️ |
| Public IP enabled | ✔️ |
| Nginx installed & running | ✔️ |
| HTML portfolio deployed | ✔️ |
| SSH | ✔️ |

---

## 📜 Deployment Commands (Linux on EC2)

```bash
sudo yum update -y
sudo yum install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo nano /usr/share/nginx/html/index.html
