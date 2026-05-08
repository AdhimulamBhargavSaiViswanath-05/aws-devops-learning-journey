# 🛠️ Deployment Steps – AWS EC2 + NGINX

## STEP 1 – Connect to EC2 Instance

```bash
ssh -i "myownkey.pem" ec2-user@13.221.40.250
```

---

# STEP 2 – Switch to Root User

```bash
sudo su
```

---

# STEP 3 – Update Packages

```bash
yum update -y
```

---

# STEP 4 – Install NGINX

```bash
yum install nginx -y
```

---

# STEP 5 – Start NGINX Service

```bash
systemctl start nginx.service
```

---

# STEP 6 – Enable NGINX on Boot

```bash
systemctl enable nginx.service
```

---

# STEP 7 – Navigate to NGINX Web Directory

```bash
cd /usr/share/nginx/html
```

---

# STEP 8 – Create Deployment Folder

```bash
sudo mkdir my-portfolio
```

---

# STEP 9 – Upload Files using SCP

```bash
scp -i "myownkey.pem" -r * ec2-user@13.221.40.250:/tmp/portfolio-upload
```

---

# STEP 10 – Copy Files to NGINX Directory

```bash
sudo cp -r /tmp/portfolio-upload/* /usr/share/nginx/html/my-portfolio/
```

---

# STEP 11 – Set Permissions

```bash
sudo chmod -R 755 /usr/share/nginx/html/my-portfolio
```

---

# STEP 12 – Restart NGINX

```bash
sudo systemctl restart nginx
```

---

# STEP 13 – Access Website

```text
http://13.221.40.250/my-portfolio/
```

---

🚀 Deployment Completed Successfully
