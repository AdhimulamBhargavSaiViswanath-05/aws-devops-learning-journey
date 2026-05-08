# 💻 Commands Used – Day 3 Deployment

## 🔐 SSH Connection

```bash
ssh -i "myownkey.pem" ec2-user@13.221.40.250
```

---

# 👑 Root Access

```bash
sudo su
```

---

# 📦 Package Update

```bash
yum update -y
```

---

# 🌐 Install NGINX

```bash
yum install nginx -y
```

---

# ▶️ Start NGINX

```bash
systemctl start nginx.service
```

---

# 🔄 Enable NGINX

```bash
systemctl enable nginx.service
```

---

# 📂 Navigate to Web Directory

```bash
cd /usr/share/nginx/html
```

---

# 📁 Create Folder

```bash
mkdir my-portfolio
```

---

# 📤 Upload Files using SCP

```bash
scp -i "myownkey.pem" -r * ec2-user@13.221.40.250:/tmp/portfolio-upload
```

---

# 📋 Copy Deployment Files

```bash
sudo cp -r /tmp/portfolio-upload/* /usr/share/nginx/html/my-portfolio/
```

---

# 🔐 Set Permissions

```bash
sudo chmod -R 755 /usr/share/nginx/html/my-portfolio
```

---

# 🔄 Restart NGINX

```bash
sudo systemctl restart nginx
```

---

# 📄 List Files

```bash
ls
```

---

# 🚪 Exit Server

```bash
exit
```

---

🚀 Day 3 Commands Documentation Completed
