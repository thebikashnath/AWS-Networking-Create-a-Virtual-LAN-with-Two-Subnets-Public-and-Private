AWS Virtual LAN with Public and Private Subnets
This repository provides the complete, step‑by‑step instructions to configure a Virtual LAN (VLAN) with two subnets — Public and Private — using the AWS Management Console and VPC networking components.
This setup ensures secure and scalable cloud networking by segmenting resources into separate subnets. Public resources (like web servers) can be accessed from the internet, while private resources (like databases) remain isolated for enhanced security.

🎯 Project Goal
The guide covers the entire manual process:
- Creating a Virtual Private Cloud (VPC).
- Defining two subnets: Public and Private.
- Configuring Internet Gateway for the Public subnet.
- Setting up a NAT Gateway to allow controlled outbound traffic from the Private subnet.
- Updating Route Tables to ensure proper traffic flow.
- Deploying sample resources (e.g., EC2 instances) into each subnet to validate connectivity.

🎥 Video Tutorial
Watch the full, hands‑on tutorial to see this configuration in action:
👉 Create a Virtual LAN with Two Subnets (Public and Private)

🚀 Getting Started
To follow along, you only need:
- An active AWS account
- Basic knowledge of networking concepts (IP addressing, gateways, routing)
Proceed to the detailed guide: ➡️ VLAN Setup Guide


📜 License
This project is licensed under the MIT License.
