# 🌐 Built My First Custom VPC on AWS

This hands-on networking project demonstrates how to create and configure a **Custom VPC** on AWS, including subnets, route tables, internet gateway, NAT gateway, and launching EC2 instances in public/private subnets.

> 🎓 AWS Beginner Project | re/Start Journey  
> 🧑‍💻 Hands-on with VPC, Subnets, NAT, EC2, Route Tables

---

## 📋 Project Summary

| Component            | Action Taken |
|----------------------|--------------|
| ✅ VPC Created        | CIDR: `10.0.0.0/16` |
| ✅ Public Subnet      | Added with auto-assign public IP |
| ✅ Private Subnet     | Added with no public IP |
| ✅ Internet Gateway   | Attached to VPC |
| ✅ NAT Gateway        | For private subnet internet access |
| ✅ Route Tables       | Separate for public & private |
| ✅ EC2 Instances      | Windows EC2 in both subnets |
| ✅ Connectivity Test  | Ping + RDP verified |

📄 [View the full PDF report here](AWS-Custom-VPC-Project.pdf)

---

## 🧠 Key Learnings

- Created a **Custom VPC** manually without wizard
- Understood **public vs private subnets**
- Used **NAT Gateway** for internet access in private subnet
- Configured **route tables**, **IGW**, **elastic IPs**, and more
- Practiced **EC2 provisioning** in a secure network setup

---

## 🔐 Security Best Practices

- Restricted RDP (port 3389) access to **my IP only**
- Ensured private EC2 had no public IP
- Terminated EC2s after testing to avoid charges

---

## 🙋‍♂️ About Me

I’m **Sayyed Hasir**, building my cloud skills through the AWS re/Start program.  
This is my third hands-on project and first deep dive into AWS networking!

---
## 🔗 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/hasir-sayyed-b16520245?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) 



