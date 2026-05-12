# ☁️ Day 5 – Windows Server Creation & RDP Connection using AWS EC2

## 📌 Objective

The objective of today’s session was to create a Windows Server instance using AWS EC2 and connect to it remotely using the RDP (Remote Desktop Protocol) client.

This practical session helped in understanding how cloud-hosted Windows systems can be accessed and managed remotely through AWS cloud infrastructure.

---

# 🚀 Topics Covered

- Creating a Windows EC2 Instance
- Selecting Windows AMI
- Creating a New Key Pair (.pem)
- Configuring Network Settings
- Launching Windows Server
- Connecting using RDP Client
- Downloading Remote Desktop File
- Decrypting Administrator Password
- Remote Desktop Authentication
- Accessing Cloud-Based Windows Server

---

# ☁️ AWS Services Used

| Service | Purpose |
|---|---|
| AWS EC2 | Virtual Cloud Server |
| Windows Server AMI | Operating System |
| RDP Client | Remote Desktop Connection |
| PEM Key Pair | Secure Authentication |

---

# 🖥️ EC2 Windows Server Creation Steps

## Step 1 — Open AWS EC2 Service

- Open AWS Management Console
- Navigate to EC2 Dashboard
- Click on Launch Instance

---

## Step 2 — Configure Instance

- Enter the server name
- Select Windows Server AMI
- Create a new Key Pair (.pem)
- Configure network settings
- Enable HTTP and HTTPS traffic
- Configure storage

---

## Step 3 — Launch Instance

- Click Launch Instance
- Wait until the instance status becomes Running

---

# 🔐 Connecting to Windows Server using RDP

After launching the Windows EC2 instance:

- Open the instance details
- Click Connect
- Select RDP Client option

Available connection methods observed:

- SSM Session Manager
- RDP Client
- EC2 Serial Console

The RDP Client option was used for this session.

---

# 📥 Remote Desktop File

- Downloaded the Remote Desktop (.rdp) file
- Opened the RDP file from local system

---

# 🔑 Password Decryption Process

To connect securely:

- Clicked Get Password
- Uploaded the previously created PEM key file
- Clicked Decrypt Password

AWS generated the administrator password successfully.

---

# 🖥️ Remote Desktop Connection

- Opened the downloaded RDP file
- Entered the decrypted password
- Accepted connection permissions
- Successfully connected to the remote Windows Server

The connected environment looked similar to a normal Windows operating system, but it was actually running remotely on AWS cloud infrastructure.

---

# 🌐 Understanding Cloud-Based Remote Systems

One important observation from today’s session was understanding the difference between:

- Local system access
- Cloud-hosted remote system access

The remote Windows server was running on AWS cloud infrastructure and accessed through the internet using RDP protocol.

This helped in understanding how cloud providers make systems accessible globally through distributed cloud servers located in different regions and availability zones.

---

# 🧠 Real-World Understanding

Today’s practical session also helped relate cloud computing concepts to real-world applications.

Large-scale platforms such as:

- Amazon
- Flipkart
- Google Services

use cloud infrastructure to manage:

- global accessibility
- large-scale user traffic
- database operations
- scalability
- uninterrupted service availability

This practical session helped connect theoretical cloud concepts with real-world implementations.

---

# 💡 Key Learnings

- Creating Windows Server using AWS EC2
- Understanding Windows AMI selection
- Configuring cloud-based Windows systems
- Using PEM keys for secure authentication
- Connecting using Remote Desktop Protocol (RDP)
- Understanding remote cloud infrastructure access
- Difference between local systems and cloud-hosted systems

---

# 🎯 Outcome

Successfully created a Windows EC2 server and connected to it remotely using RDP client through AWS cloud infrastructure.

---

🚀 Day 5 Completed Successfully
