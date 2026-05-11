# ☁️ Day 4 – Ubuntu Server Setup & Website Deployment using Apache2

## 📌 Objective

The objective of Day 4 was to create and configure an Ubuntu server on AWS EC2 and deploy a basic website using the Apache2 web server.

This session provided practical exposure to Ubuntu server management, Apache2 configuration, and direct website deployment using Linux terminal operations.

---

# 🚀 Topics Covered

- Creating Ubuntu EC2 Instance
- Connecting to Ubuntu Server
- Installing Apache2 Web Server
- Starting Apache2 Service
- Understanding Default Apache Webpage
- Deploying Custom HTML Website
- Editing Files using Nano Editor
- Linux Terminal Operations

---

# ☁️ AWS Infrastructure Used

| Service | Purpose |
|---|---|
| AWS EC2 | Virtual Cloud Server |
| Ubuntu Server | Operating System |
| Apache2 | Web Server |
| SSH | Secure Remote Access |

---

# 💻 Commands Executed

## Switch to Root User

```bash
sudo su -
```

---

## Update Ubuntu Packages

```bash
apt-get update -y
```

---

## Install Apache2

```bash
apt-get install apache2 -y
```

---

## Start Apache2 Service

```bash
service apache2 start
```

---

# 🌐 Apache2 Verification

After installation and service startup, the default Apache webpage was displayed successfully through the EC2 public IP address.

Example:

```text
http://54.89.85.223/
```

This confirmed that the Apache2 web server was running successfully.

---

# 📂 Website Deployment

Moved into Apache web directory:

```bash
cd /var/www/html
```

Created and edited website files using Nano editor:

```bash
nano filename.html
```

The default webpage was replaced with a custom webpage successfully.

---

# ✏️ Nano Editor Shortcuts Learned

| Shortcut | Purpose |
|---|---|
| `Ctrl + O` | Save File |
| `Enter` | Confirm Save |
| `Ctrl + X` | Exit Nano Editor |

---

# 🧠 Key Learnings

- Creating Ubuntu server in AWS EC2
- Installing and managing Apache2 web server
- Hosting a static webpage on Ubuntu server
- Editing files directly using Nano editor
- Understanding Linux-based deployment workflows
- Managing website files inside Apache web directory

---

# 🚀 Personal Learning Experience

Today’s session helped me understand Ubuntu server deployment workflows more clearly.

Since I already had deployment experience from Day 3 using Amazon Linux and NGINX, today’s practical implementation using Ubuntu and Apache2 became easier to understand and execute.

I also learned how to edit and modify files directly inside the Linux terminal using Nano editor, which improved my confidence in handling server-side configurations and deployments.

This session increased my practical understanding of Cloud Computing and DevOps concepts.

---

# 🎯 Outcome

Successfully created an Ubuntu EC2 server, installed Apache2 web server, and deployed a custom webpage publicly using AWS cloud infrastructure.

---

🚀 Day 4 Completed Successfully
