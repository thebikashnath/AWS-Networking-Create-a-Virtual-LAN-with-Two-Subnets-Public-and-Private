# VLAN Setup Guide

## Step 1: Create a VPC
- Go to AWS Management Console → VPC → Create VPC
- Assign CIDR block (e.g., 10.0.0.0/16)

## Step 2: Create Subnets
- Public Subnet: 10.0.1.0/24
- Private Subnet: 10.0.2.0/24

## Step 3: Configure Internet Gateway
- Attach IGW to VPC
- Update Public Route Table → 0.0.0.0/0 → IGW

## Step 4: Configure NAT Gateway
- Deploy NAT Gateway in Public Subnet
- Update Private Route Table → 0.0.0.0/0 → NAT Gateway

## Step 5: Launch EC2 Instances
- Public Subnet → Web server (with public IP)
- Private Subnet → Database server (no public IP)

## Step 6: Test Connectivity
- Access web server from browser
- Verify private instance connects to internet via NAT
