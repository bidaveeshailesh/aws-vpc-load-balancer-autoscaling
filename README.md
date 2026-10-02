# AWS VPC, Load Balancer & Auto Scaling

## 📌 Project Overview

This project demonstrates how to build a scalable application environment in AWS using **Amazon VPC, EC2, Application Load Balancer, and Auto Scaling**.

The architecture is designed to distribute incoming application traffic across EC2 instances and automatically adjust the number of instances based on demand.

## 🏗️ Architecture

```text
                    Internet
                       |
                       v
              Application Load Balancer
                       |
              +--------+--------+
              |                 |
              v                 v
           EC2 Instance      EC2 Instance
              |                 |
              +--------+--------+
                       |
                 Auto Scaling
                       |
                 Amazon VPC
```

## ☁️ AWS Services Used

- **Amazon VPC** — Provides the isolated network environment.
- **Amazon EC2** — Runs the application servers.
- **Application Load Balancer** — Distributes incoming traffic across EC2 instances.
- **Auto Scaling** — Helps maintain the required number of EC2 instances.
- **AWS IAM** — Manages access and permissions.

## ⚙️ How It Works

1. Create an Amazon VPC with the required networking components.
2. Launch EC2 instances inside the VPC.
3. Configure an Application Load Balancer.
4. Register EC2 instances with the target group.
5. Configure an Auto Scaling Group.
6. Route incoming traffic through the Load Balancer.
7. Auto Scaling can add or remove EC2 instances according to configured conditions.

## 🔐 Security

The project uses AWS security controls such as:

- Security Groups
- IAM permissions
- Public and private subnet concepts
- Controlled inbound and outbound traffic

## 🛠️ Technologies Used

- AWS VPC
- Amazon EC2
- Application Load Balancer
- Auto Scaling
- AWS IAM
- Git & GitHub

## 🎯 What I Learned

- AWS VPC fundamentals
- EC2 instance deployment
- Application Load Balancer configuration
- Target groups
- Auto Scaling Groups
- AWS networking concepts
- Basic cloud security
- How to document AWS projects using GitHub

## 📂 Project Type

**Cloud / AWS / Networking / DevOps**

## 👨‍💻 Author

**Shailesh Bidave**

GitHub: [@bidaveeshailesh](https://github.com/bidaveeshailesh)
