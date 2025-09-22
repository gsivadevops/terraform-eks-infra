# terraform-eks-infra
Terraform project to provision AWS infrastructure for EKS, including VPC, subnets, security groups, ACM certificate, ingress load balancer, and bastion host.

# Terraform EKS Infrastructure

This repository contains Terraform code to provision a **production-ready Amazon EKS cluster** along with the required AWS infrastructure.  
It automates the creation of networking, security, bastion access, and ingress load balancer configuration for deploying workloads.

---

## 🚀 Features
- **VPC Creation**  
  - Public and private subnets  
  - Internet Gateway & NAT Gateway  
  - Route tables  

- **Security Groups**  
  - Cluster security groups  
  - Worker node security groups  
  - Bastion host security group  

- **EKS Cluster**  
  - Managed node groups  
  - Cluster IAM roles & policies  

- **Ingress & SSL**  
  - AWS Load Balancer Controller setup  
  - ACM (AWS Certificate Manager) certificate for TLS/HTTPS  

- **Bastion Host**  
  - EC2 instance for secure access to private subnets  
  - Key pair authentication  

---


