# AWS Networking: Create a Virtual LAN with Two Subnets (Public and Private)

This repository demonstrates how to set up a **Virtual LAN (VLAN)** with two subnets:
- **Public Subnet**: For resources that require internet access (e.g., web servers).
- **Private Subnet**: For internal resources (e.g., databases, application servers) secured from direct internet exposure.

## 🚀 Features
- Step-by-step guide to creating a VLAN in AWS
- Clear architecture diagrams for Public and Private subnets
- Example configurations using AWS VPC, routing tables, Internet Gateway, and NAT Gateway
- Infrastructure-as-Code samples (Terraform/CloudFormation) for reproducible deployment

## 🛠️ Prerequisites
- AWS account
- Basic networking knowledge (IP addressing, subnets, gateways)
- Tools: AWS CLI / Terraform / CloudFormation

## 📂 Repository Contents
- `diagrams/` → Architecture diagrams
- `src/` → Infrastructure code samples
- `docs/` → Additional notes and tutorials

## 📸 Thumbnail
![Thumbnail](diagrams/vlan-thumbnail.png)

## 📜 License
This project is licensed under the MIT License.
