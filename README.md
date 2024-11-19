# Cloud Audit Playbooks

A collection of Terraform configurations for auditing AWS, Azure, and GCP tenants. These playbooks query resources, networking, IAM setups, and security configurations, providing a comprehensive overview of your cloud environments.

## 📋 Features

- **AWS Audit**: Discovers EC2 instances, S3 buckets, IAM policies, and security groups.
- **Azure Audit**: Lists resource groups, virtual machines, storage accounts, and RBAC policies.
- **GCP Audit**: Queries Compute Engine instances, GCS buckets, and IAM roles.

## 🚀 Getting Started

1. **Install Terraform**:
   Download Terraform from the [official website](https://www.terraform.io/downloads).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/moussan/cloud-audit-playbooks.git
   cd cloud-audit-playbooks
