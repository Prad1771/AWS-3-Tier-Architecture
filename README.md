# AWS-3-Tier-Architecture
# AWS 3-Tier Architecture Project

## Project Overview
This project demonstrates the deployment of a highly available and scalable AWS 3-Tier Architecture.
The architecture separates the application into three layers:

1. Presentation Layer (Web Tier)
2. Application Layer (Business Logic Tier)
3. Database Layer (Data Tier)

The design follows AWS best practices for security, scalability, and high availability.
---

## Architecture Components
### Networking
* Amazon VPC
* Public Subnets
* Private Subnets
* Internet Gateway
* Route Tables
* Security Groups
* NAT Gateway

### Web Tier
* EC2 Instances
* Application Load Balancer (ALB)
* Auto Scaling Group

### Application Tier
* Private EC2 Instances
* Application Services

### Database Tier
* Amazon RDS MySQL
* Multi-AZ Deployment
* Automated Backups
---

## AWS Services Used
* Amazon EC2
* Amazon VPC
* Amazon RDS
* Elastic Load Balancer
* Auto Scaling Group
* Security Groups
* CloudWatch
* IAM
---

## Project Workflow
User Request
↓
Application Load Balancer
↓
Web Tier EC2 Instances
↓
Application Tier EC2 Instances
↓
RDS Database
---

## Key Features
* High Availability
* Scalability
* Fault Tolerance
* Secure Network Design
* Load Balancing
* Automated Scaling
* Database Backup and Recovery
---

## Security Implementation
* Private Subnets for Application Tier
* Private Subnets for Database Tier
* Security Group Restrictions
* IAM Role-Based Access
* Network Segmentation
---

## Outcome
Successfully designed and implemented a secure and scalable AWS 3-Tier Architecture capable of handling application traffic while maintaining security and high availability.
