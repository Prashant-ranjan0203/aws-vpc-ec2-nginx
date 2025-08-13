# Terraform AWS VPC + EC2 + Nginx
## Overview
This Terraform project creates:
- AWS VPC (`10.0.0.0/16`)
- Public & Private Subnets
- Internet Gateway & Route Tables
- EC2 Instance running Nginx
- Security Group allowing HTTP (80) and SSH (22)
- The EC2 instance is automatically configured with user data to install and start Nginx upon launch.

- ## Architecture Diagram

![AWS VPC + EC2 + Nginx Architecture](https://github.com/Prashant-ranjan0203/aws-vpc-ec2-nginx/blob/main/project-diagram.png?raw=true)

- ## Requirements
- Terraform CLI v1.5+
- AWS CLI configured with valid credentials

## Usage
 bash
terraform init
terraform validate
terraform plan
terraform apply


