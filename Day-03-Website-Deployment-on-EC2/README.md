# 🚀 Day 3 – Portfolio Website Deployment on AWS EC2 using NGINX

## 📌 Objective

The objective of Day 3 was to deploy a static portfolio website on an AWS EC2 Linux server using the NGINX web server.

This practical implementation helped in understanding real-world cloud deployment workflows, remote server management, Linux operations, and static web hosting.

---

# ☁️ AWS Infrastructure Used

| Service | Purpose |
|---|---|
| AWS EC2 | Virtual Cloud Server |
| Amazon Linux 2023 | Operating System |
| NGINX | Web Server |
| SSH | Secure Remote Access |
| SCP | File Transfer |

---

# 🖥️ Project Overview

A responsive portfolio website developed using:
- HTML
- CSS
- JavaScript

was deployed on an AWS EC2 instance and served publicly through the NGINX web server.

---

# 🔄 Deployment Workflow

```text
Local Laptop (PowerShell)
        ↓
SCP File Transfer
        ↓
AWS EC2 Linux Server
        ↓
NGINX Web Server
        ↓
Live Website Deployment
```

---

# 🔑 Key Activities Performed

- Connected to EC2 instance using SSH
- Installed and configured NGINX
- Created deployment directory
- Uploaded website files using SCP
- Copied files into NGINX web directory
- Configured file permissions
- Restarted NGINX service
- Successfully hosted website publicly

---

# 🌐 Live Deployment

```text
http://13.221.40.250/my-portfolio/
```

📌 Note:
This deployment is hosted on a temporary AWS Academy EC2 instance used for learning purposes. The public IP address may change in future sessions.

---

# 💻 Technologies & Tools Used

- AWS EC2
- Amazon Linux 2023
- NGINX
- SSH
- SCP
- Linux Terminal
- HTML
- CSS
- JavaScript

---

# 🧠 Key Learnings

- Practical AWS EC2 deployment
- Linux server management
- SSH remote connectivity
- SCP file transfer workflow
- NGINX web server configuration
- Static website hosting
- File permissions management

---

# 🎯 Outcome

Successfully deployed and hosted a static portfolio website on AWS EC2 using NGINX web server.

This implementation provided practical exposure to real cloud deployment workflows and server-side application hosting.

---

🚀 First Real Cloud Deployment Completed Successfully
