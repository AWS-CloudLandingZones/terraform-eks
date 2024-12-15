# Terraform EKS Cluster Setup

This project contains a robust and reusable Terraform configuration to deploy an enterprise-grade Amazon EKS (Elastic Kubernetes Service) cluster. It includes advanced settings for storage, networking, logging, and proxies, along with a Makefile for Terraform operations and a GitHub Actions workflow for CI/CD.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Terraform Files](#terraform-files)
- [Makefile](#makefile)
- [GitHub Actions Workflow](#github-actions-workflow)
- [Variables](#variables)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites
- [Terraform](https://www.terraform.io/downloads.html) v1.0.11 or later
- AWS CLI configured with the appropriate permissions
- GitHub account for repository management and Actions
- SSH key pair created in AWS

## Setup Instructions
1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

