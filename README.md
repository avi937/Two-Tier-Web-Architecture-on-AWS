Two-Tier Joomla CMS Architecture on AWS

This project demonstrates a fully functional two-tier architecture on AWS, deploying Joomla CMS on EC2 instances running Amazon Linux and connecting to a MySQL RDS database in private subnets. An Application Load Balancer (ALB) ensures high availability and traffic distribution across instances.

Architecture Overview

Web Tier: Joomla CMS running on EC2 instances in public subnets

Database Tier: MySQL RDS hosted in private subnets

Traffic Management: Application Load Balancer (ALB) for load balancing and fault tolerance

Security: Custom VPC, Security Groups, and least-privilege access

[ Users ]
   ↓
[ EC2 Instances (Joomla CMS) ]  ← HTTP (80)
   ↓
[ RDS MySQL Database ]         ← MySQL (3306)

Key Features ✅

Custom VPC with public/private subnets for secure network segmentation

EC2 instances configured with Apache, PHP, and Joomla CMS

Private RDS MySQL database connected securely from EC2

Application Load Balancer (ALB) distributing traffic across multiple instances

Security Groups enforcing least-privilege access

EC2 instances only accept traffic via the ALB

Designed for scalability, availability, and production readiness

Skills & Experience Gained

Networking & Subnet Planning

Infrastructure Security Best Practices

Load Balancing & High Availability

Frontend-Backend Connectivity in a Secure Cloud Environment

Using Amazon Linux for EC2 deployment

Outcome

Successfully deployed a secure, scalable, and highly available Joomla CMS application on AWS, reflecting real-world cloud architecture practices.

Tags: AWS DevOps Joomla EC2 RDS ALB AmazonLinux CloudArchitecture HighAvailability
