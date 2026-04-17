![Project Status](https://img.shields.io/badge/status-completed-brightgreen)
 # 🚀 AWS EC2 Web Server Project

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

