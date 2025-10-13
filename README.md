# 🚀 **Provision Amazon EKS Cluster on AWS using Terraform**  
## 🔥 **Introduction**  
### 🟢 What is Amazon EKS?  
Amazon Elastic Kubernetes Service (**Amazon EKS**) is a **fully managed** Kubernetes service that simplifies deploying, managing, and scaling containerized applications on AWS.  
### 🟢 What is Terraform?  
Terraform is an **open-source Infrastructure as Code (IaC) tool** that enables declarative provisioning and management of cloud infrastructure.  
---
## ✅ **Prerequisites**  
Before proceeding, ensure you have the following:  
- **AWS Account** (Free Tier Available)  
- **AWS CLI** ([Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html))  
- **Terraform** ([Install Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli))  
- **Kubectl** ([Install Kubectl](https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html))  
- **VS Code** (Recommended IDE)  
---
## 📂 **Project Structure**  
```bash
📦 eks-cluster-terraform
├── 📜 provider.tf               # AWS Provider Configuration
├── 📜 eks-backend-terra.tf       # S3 Backend for Terraform State
├── 📜 vpc.tf                     # VPC Configuration
├── 📜 subnets.tf                 # Public Subnets
├── 📜 internetgw.tf              # Internet Gateway
├── 📜 route.tf                   # Route Table
├── 📜 sg.tf                      # Security Groups
├── 📜 iam_role.tf                # IAM Roles & Policies
├── 📜 eks_cluster.tf             # EKS Cluster Configuration
├── 📜 eks_node_group.tf          # EKS Worker Nodes
└── 📜 README.md                  # Project Documentation
```  
---
## 📚 **References**  
- **[Terraform Registry](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs)**  
- **[AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)**  
- **[EKS Documentation](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)**  
🔗 _This project follows AWS best practices for EKS deployment using Terraform._  
## 🎯 **YOLO Badge Update**
This change is made to demonstrate the YOLO GitHub achievement - creating and merging a PR without code review!

## 🦈 **Pull Shark Badge - Update 1**
Adding this section for the Pull Shark achievement!
