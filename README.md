Three-Tier High Availability Architecture on AWS using Terraform
This project demonstrates the automated deployment of a scalable, load-balanced three-tier architecture on AWS using Terraform. It showcases infrastructure-as-code principles and best practices for building fault-tolerant systems.

Project Overview
The infrastructure includes:

Web Tier: EC2 instances behind an Application Load Balancer (ALB) to serve client requests
Application Tier: EC2 instances responsible for processing business logic
Database Tier: Simulated using EC2 instances (for demonstration purposes)
Each tier is distributed across multiple AWS Availability Zones to ensure high availability and resilience.

Infrastructure Components
Virtual Private Cloud (VPC) with public and private subnets
Application Load Balancer (ALB) with listener and target groups
EC2 instances with proper IAM roles and security groups
Route tables, internet gateway, and NAT configuration
Modular Terraform configuration with lifecycle commands:
terraform init
terraform plan
terraform apply
Technologies Used
AWS EC2, ALB, VPC, Security Groups
Terraform (HCL)
Shell (for provisioning logic)
Outcome
This automated setup reduces deployment time significantly and provides a reusable pattern for scalable AWS architectures. It reflects strong understanding of DevOps principles, infrastructure automation, and cloud-native design.
