# 🚀 AWS EC2 Web Server Project

![Project Status](https://img.shields.io/badge/status-completed-brightgreen)
![Cloud](https://img.shields.io/badge/cloud-AWS-orange)
![Level](https://img.shields.io/badge/level-beginner-blue)

---

## 🧠 Architecture

This project uses a simple cloud architecture:

User → Internet → EC2 (Web Server)

---

## 📌 Key Features

* Deployed a live web server on AWS
* Configured secure access using Security Groups
* Installed and managed Apache service
* Hosted a static website

---




## 📌 Project Overview

This project demonstrates how to launch and configure a web server on AWS EC2.

## 🛠️ Tools & Services Used

* Amazon EC2
* Amazon Linux 2
* Apache (httpd)
* Security Groups

## ⚙️ Steps Performed

### 1. Launched EC2 Instance

* Instance type: t2.micro (Free Tier)
* OS: Amazon Linux 2

### 2. Configured Security Group

* Allowed SSH (Port 22)
* Allowed HTTP (Port 80)

### 3. Installed Web Server

```bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
```

### 4. Created Sample Web Page

```bash
echo "<h1>Welcome Umar Cloud Project 🚀</h1>" | sudo tee /var/www/html/index.html
```

## 🌐 Output

Successfully hosted a static web page using EC2.

## 📸 Screenshots

**EC2 instance running**

<img width="790" height="344" alt="EC2 instance running Captures-1" src="https://github.com/user-attachments/assets/ea27ead3-a1a7-4fb0-b766-ea738b2aab45" />

**Security group rules**

<img width="871" height="320" alt="SecurityGroup Capture-2" src="https://github.com/user-attachments/assets/b2d04da2-302c-4ea4-b7f5-09d5d9417b6e" />

**Browser output (website)**

<img width="931" height="401" alt="Browser output Capture-3" src="https://github.com/user-attachments/assets/74b7c190-16f5-4a10-b8a1-93b96900d44f" />


## 📚 Learning Outcome

* Understood EC2 instance setup
* Learned basic Linux commands
* Configured web server on cloud

---

✨ This is my first step into Cloud & DevOps journey.


## 💼 Resume Impact

This project demonstrates:

* Cloud infrastructure setup using AWS EC2
* Basic system administration (Linux)
* Web server deployment and configuration
* Understanding of networking (ports, security groups)

---
## 🌐 VPC Setup

### 📌 Overview

Created a custom Virtual Private Cloud (VPC) to simulate a real-world cloud network architecture.

### ⚙️ Configuration

* VPC CIDR: 10.0.0.0/16
* Public Subnet: 10.0.1.0/24
* Private Subnet: 10.0.2.0/24

### 🔐 Components Configured

* Internet Gateway attached to VPC
* Route Table configured for public subnet
* Enabled internet access for public subnet

### 📚 Learning Outcome

* Understood VPC architecture
* Learned subnetting and routing
* Configured secure and scalable network structure
  
### 📸 VPC Screenshots
**VPC**
<img width="1873" height="725" alt="My VPC" src="https://github.com/user-attachments/assets/2988fa96-68d3-4c34-a422-6a88cdaec080" />

**Subnets**
<img width="1918" height="698" alt="Public   Private Subnets" src="https://github.com/user-attachments/assets/0d98478e-8fb0-4295-8c4b-44c27e04dbc8" />

**Route Table**
<img width="1920" height="715" alt="Public Route table" src="https://github.com/user-attachments/assets/7a9812d6-de7f-4088-a8b8-e8ddd9d3d198" />

**IGW**
<img width="1882" height="753" alt="My IGW" src="https://github.com/user-attachments/assets/19845bf4-d267-4fec-80f6-5473ce58c936" />

## 🚀 EC2 Deployment in Custom VPC

### 📌 Overview

Launched an EC2 instance inside a custom VPC and public subnet.

### ⚙️ Configuration

* VPC: My-VPC
* Subnet: Public-Subnet
* Public IP: Enabled

### 🔧 Setup

* Installed Apache web server
* Hosted a static website

### 📚 Learning Outcome

* Understood EC2 deployment inside VPC
* Learned subnet-based architecture
* Configured internet access for instances

### 📸 Screenshots

**EC2 inside VPC
Subnet selected**

<img width="1920" height="751" alt="EC2 inside VPC   Subnet selected" src="https://github.com/user-attachments/assets/ada13571-e6b4-461a-80d2-776b28832bb9" />

**Website output**

<img width="1920" height="638" alt="Website output" src="https://github.com/user-attachments/assets/9aa65412-e320-4b72-afd2-45a51dc2b663" />



