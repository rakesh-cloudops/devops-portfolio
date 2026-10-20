# AWS Infrastructure with Terraform

## Overview
A hands-on Infrastructure as Code project that defines an AWS EC2 instance and a security group using Terraform.

## Technologies
- Terraform
- AWS EC2
- AWS Security Groups
- Git and GitHub

## Infrastructure
- EC2 instance
- Security group with SSH and HTTP rules
- AWS region: `ap-south-1`

## Prerequisites
- Terraform installed
- AWS credentials configured securely
- Valid AMI ID and EC2 key pair in the selected region

## Workflow
```bash
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply
```

Review the plan before applying changes.

When the practice resources are no longer needed, review and run:
```bash
terraform destroy
```

## Security Notes
Restrict SSH access to a trusted IP address instead of `0.0.0.0/0`. Check the AMI and key-pair settings before deployment. Never commit AWS credentials or private keys.

Creating an EC2 instance does not automatically install a web server.

## Original Repository
https://github.com/rakesh-cloudops/terraform-practical
