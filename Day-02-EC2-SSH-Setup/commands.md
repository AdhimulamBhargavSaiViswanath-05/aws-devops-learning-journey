# 💻 Day 2 Commands – EC2 & SSH Setup

## 🔐 SSH Connection

```bash
ssh -i "myownkey.pem" ec2-user@<PUBLIC-IP>
```

Used to connect securely to the EC2 Linux server.

---

# 📂 Linux Basic Commands

## Show Current Directory

```bash
pwd
```

---

## List Files & Folders

```bash
ls
```

---

## Change Directory

```bash
cd <folder-name>
```

Example:

```bash
cd /usr/share/nginx/html
```

---

## Create New Folder

```bash
mkdir my-portfolio
```

---

## Clear Terminal

```bash
clear
```

---

## Logout from Server

```bash
exit
```

---

# 📝 Notes

- `.pem` file should be stored securely.
- Security Groups must allow SSH access on Port 22.
- Public IP address is required for remote SSH connection.
- Amazon Linux default username:
  
```bash
ec2-user
```

---

🚀 Day 2 Practical Commands Completed
