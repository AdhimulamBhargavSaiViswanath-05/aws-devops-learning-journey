# 🔐 Day 2 – EC2 Instance Setup & SSH Access

## 📌 Objective

The objective of Day 2 was to gain practical experience with AWS EC2 instances, understand SSH authentication, connect to a Linux server remotely, and explore basic Linux terminal operations.

---

# ☁️ Introduction to Amazon EC2

Amazon EC2 (Elastic Compute Cloud) is a virtual server service provided by AWS that allows users to launch and manage cloud-based virtual machines.

EC2 enables:
- Virtual server hosting
- Scalable infrastructure
- Remote server access
- Cloud-based application deployment

---

# 🖥️ EC2 Instance Setup

During this session, an EC2 instance was launched using:

- Amazon Linux 2023 AMI
- t3.micro Instance Type
- AWS Academy Environment

The instance was configured with:
- Public IP address
- Security Groups
- SSH access permissions

---

# 🔑 Understanding Key Pairs

AWS uses Key Pair Authentication for secure remote access.

## Key Pair Components

### Public Key
Stored inside the EC2 instance.

### Private Key (.pem file)
Stored securely on the local system and used for SSH authentication.

Example:
```bash
myownkey.pem
```

The `.pem` file is required to establish a secure connection between the local system and the EC2 server.

---

# 🔐 SSH Connection

SSH (Secure Shell) is used to securely connect to remote Linux servers.

## SSH Command Used

```bash
ssh -i "myownkey.pem" ec2-user@<PUBLIC-IP>
```

### Components
- `ssh` → Secure Shell command
- `-i` → Specifies PEM key file
- `ec2-user` → Default Amazon Linux username
- `<PUBLIC-IP>` → EC2 public IP address

---

# 🐧 Linux Terminal Basics

Basic Linux terminal commands were explored during the session.

## Common Commands

| Command | Purpose |
|---|---|
| `pwd` | Show current directory |
| `ls` | List files and folders |
| `cd` | Change directory |
| `mkdir` | Create folder |
| `clear` | Clear terminal |
| `exit` | Logout from server |

---

# 🛡️ Security Groups

Security Groups act as virtual firewalls for EC2 instances.

The following rules were enabled:
- SSH (Port 22)
- HTTP (Port 80)

These rules allowed:
- Remote SSH connection
- Web server access

---

# 🧠 Key Learnings

- Introduction to AWS EC2
- Launching a Linux virtual machine
- Understanding PEM key authentication
- Connecting remotely using SSH
- Basic Linux terminal usage
- Importance of security groups

---

# 🎯 Outcome

Day 2 provided practical exposure to real AWS cloud infrastructure and remote Linux server management using SSH authentication.

This session served as the foundation for upcoming deployment and DevOps practical implementations.

---

🚀 Practical Cloud Journey Continues...
