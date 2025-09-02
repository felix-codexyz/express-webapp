# Terraform Infrastructure

This document describes the Terraform configuration used to provision the AWS infrastructure for the application.

**Note:** The Terraform modules in the `terraform/modules/` directory are placeholders. They need to be populated with the actual infrastructure code.

## Overview

The Terraform configuration is located in the `terraform/` directory. The `environments/dev/` directory contains the configuration for the development environment.

The infrastructure will consist of:
- A Virtual Private Cloud (VPC)
- An Amazon Elastic Kubernetes Service (EKS) cluster
- An Application Load Balancer (ALB)
- An Amazon Relational Database Service (RDS) instance
- An Amazon Elastic Container Registry (ECR) repository
- AWS Identity and Access Management (IAM) roles and policies
- AWS Secrets Manager secrets
- Security Groups
- A Bastion host

## Modules

The configuration will use local Terraform modules from the `terraform/modules/` directory. Each subdirectory in `terraform/modules/` will contain a module for a specific component of the infrastructure.
