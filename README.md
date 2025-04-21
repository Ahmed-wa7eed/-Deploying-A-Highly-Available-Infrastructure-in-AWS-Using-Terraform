# 🚀 AWS Terraform Infrastructure Project

This project builds a complete AWS infrastructure using **Terraform**. It includes a VPC, public and private subnets, NAT gateway, EC2 instances, Application Load Balancer (ALB), Auto Scaling Group, and an RDS database.

---

## 📁 Project Structure

- **VPC** with CIDR block defined by variables
- **Public & Private Subnets** across multiple availability zones
- **Internet Gateway** for public subnets
- **NAT Gateway** for internet access from private subnets
- **Security Groups** for EC2, ALB, and RDS
- **EC2 Instances** in private subnets with Apache installed
- **Application Load Balancer** routing HTTP traffic
- **Auto Scaling Group** for scalable EC2 deployment
- **RDS MySQL Database** in private subnets

---

## 🧰 Technologies Used

- **Terraform**
- **AWS**
- **HCL (HashiCorp Configuration Language)**
- **Git / GitHub**

---

## 🔧 How to Use

### 1. 📥 Clone the Repo

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
