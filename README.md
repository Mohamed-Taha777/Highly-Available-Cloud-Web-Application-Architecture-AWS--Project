# Highly-Available-Cloud-Web-Application-Architecture-AWS--Project
Highly available 3-tier AWS architecture using EC2, ALB, Auto Scaling, RDS, and VPC to deliver a secure, scalable, and fault-tolerant web application.




## Project Overview

This project demonstrates the design and deployment of a highly available and scalable 3-tier web application architecture on AWS. The solution follows cloud best practices by separating the infrastructure into presentation, application, and database tiers while ensuring security, fault tolerance, and scalability.

## Architecture

### Web Tier

* Application Load Balancer (ALB)
* Public Subnets
* Internet-facing access

### Application Tier

* EC2 Instances
* Auto Scaling Group (ASG)
* Multi-AZ deployment

### Database Tier

* Amazon RDS
* Private Subnets
* Secure database access

## AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Amazon RDS
* Amazon VPC
* Security Groups
* Public & Private Subnets

## Key Features

* Highly Available Architecture
* Multi-AZ Deployment
* Auto Scaling
* Load Balancing
* Secure Network Segmentation
* Scalable Infrastructure Design

## Network Design

* Public subnets for internet-facing resources.
* Private subnets for application and database tiers.
* Security Groups configured to restrict access between layers.
* Application traffic routed through the Load Balancer.

## Project Objectives

* Build a production-style AWS infrastructure.
* Implement high availability and fault tolerance.
* Apply AWS networking and security best practices.
* Design a scalable cloud architecture.

## Architecture Diagram

*Add your AWS architecture diagram here.*

## Skills Demonstrated

* AWS Cloud Infrastructure
* High Availability (HA)
* Load Balancing
* Auto Scaling
* VPC Design
* Network Security
* Infrastructure Architecture
