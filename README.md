# AWS Basic to Advanced 🚀

Welcome to the **AWS Basic to Advanced** repository, a comprehensive guide that takes you from foundational AWS concepts to mastering complex cloud architectures. Whether you're a beginner exploring cloud computing or an advanced user building large-scale cloud infrastructure, this repository is designed to provide practical, real-world knowledge to help you succeed in AWS.

## 📚 Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [How to Use This Repo](#how-to-use-this-repo)
4. [AWS Basics](#aws-basics)
5. [Intermediate Topics](#intermediate-topics)
6. [Advanced Topics](#advanced-topics)
7. [Best Practices](#best-practices)
8. [Contributing](#contributing)
9. [Connect With Me](#connect-with-me)

---

## Introduction

Amazon Web Services (AWS) is one of the leading cloud platforms used by individuals and organizations worldwide. This repository is structured to help you learn AWS step-by-step, starting from basic services and moving up to advanced cloud architectures, DevOps practices, and serverless technologies.

### Why Use This Repository?
- **Hands-On Learning**: Gain real-world experience by following practical examples and tasks.
- **Progressive Learning Path**: Move from beginner to advanced topics with a clear learning path.
- **Comprehensive Coverage**: Covers AWS core services, security, networking, DevOps, serverless, and more.

---

## Prerequisites

To make the most of this repository, you'll need the following:

- An [AWS account](https://aws.amazon.com/free/). The Free Tier provides sufficient resources for basic and intermediate learning.
- Basic knowledge of cloud computing and networking concepts (helpful but not required).
- Installed tools:
  - AWS CLI ([installation guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html))
  - A terminal (Linux/macOS) or PowerShell (Windows)
  - Text editor like [VS Code](https://code.visualstudio.com/)

---

## How to Use This Repo

This repository is organized into sections based on the complexity of the topics. Each section contains subfolders with relevant tutorials, projects, and hands-on tasks. 

1. **Navigate** through each section based on your current knowledge level.
2. **Read the documentation** in the folder's `README.md` for step-by-step guidance.
3. **Follow the exercises** by executing commands and deploying resources in your AWS account.
4. **Review and Explore** advanced topics after completing the basics and intermediate levels.

---

## AWS Basics

The foundational topics to get you started with AWS, including:

- **Compute Services**:
  - [EC2](./basics/EC2.md): Learn how to launch and manage EC2 instances.
  - [Lambda](./basics/Lambda.md): Introduction to serverless computing.
  - Auto Scaling and Elastic Load Balancing.

- **Storage Solutions**:
  - [Amazon S3](./basics/S3.md): Master object storage, versioning, and lifecycle policies.
  - EBS and EFS: Block storage and shared file systems.

- **Networking Essentials**:
  - [VPC](./basics/VPC.md): Set up and manage Virtual Private Clouds, subnets, routing, and security groups.
  - [Route 53](./basics/Route53.md): Domain name services and routing.
  
- **Security**:
  - [IAM](./basics/IAM.md): Create and manage users, groups, and roles, and implement secure access policies.
  - MFA (Multi-Factor Authentication) for account protection.

---

## Intermediate Topics

Now that you're comfortable with the basics, explore more complex topics and real-world scenarios:

- **CI/CD Pipelines**:
  - [CodePipeline](./intermediate/CodePipeline.md): Automate build, test, and deploy phases.
  - [CodeDeploy](./intermediate/CodeDeploy.md): Automate application deployments to EC2, Lambda, etc.

- **Infrastructure as Code (IaC)**:
  - [CloudFormation](./intermediate/CloudFormation.md): Automate infrastructure provisioning and management with templates.

- **Serverless Architecture**:
  - [API Gateway](./intermediate/APIGateway.md): Build and manage APIs with Lambda as backend.
  - [DynamoDB](./intermediate/DynamoDB.md): NoSQL databases with scalability and low-latency.

- **Monitoring and Logging**:
  - [CloudWatch](./intermediate/CloudWatch.md): Monitor AWS resources, collect logs, and set alarms.
  - CloudTrail: Track user activity and API usage across AWS.

---

## Advanced Topics

Dive into complex and scalable architectures with advanced AWS services and best practices:

- **Kubernetes on AWS**:
  - [EKS](./advanced/EKS.md): Deploy and manage Kubernetes clusters on AWS.
  
- **High Availability and Scalability**:
  - Architect applications for high availability with multi-region deployments, auto-scaling, and load balancing.

- **Advanced Networking**:
  - [VPC Peering & Transit Gateway](./advanced/VPCPeering.md): Connect multiple VPCs across accounts and regions.
  - VPN & Direct Connect: Secure hybrid cloud solutions.

- **Disaster Recovery & Fault Tolerance**:
  - Implement backup strategies and disaster recovery planning using services like AWS Backup, Route 53 failover, and S3 cross-region replication.

---

## Best Practices

- **Security**: Implement least privilege policies with IAM, enable logging for audit trails (CloudTrail), and encrypt data at rest (KMS) and in transit.
- **Cost Management**: Use AWS Cost Explorer and Budgets to monitor and optimize your spending.
- **Performance Optimization**: Use auto-scaling, caching (CloudFront, ElastiCache), and RDS read replicas to optimize performance.

---

## Contributing

Contributions are what make the open-source community such a fantastic place to learn, inspire, and create. Any contributions you make are **greatly appreciated**!

To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-topic`).
3. Make your changes and commit (`git commit -m 'Add new topic'`).
4. Push the branch (`git push origin feature/new-topic`).
5. Open a Pull Request.

---

## Connect With Me

Feel free to reach out if you have any questions or suggestions:

- **LinkedIn**: [Ashish Nitin Makasare](https://www.linkedin.com/in/ashish-nitin-makasare/)
- **GitHub**: [Ashishm96](https://github.com/Ashishm96)
- **Email**: [ashishmakasare24@gmail.com](mailto:ashishmakasare24@gmail.com)

---

This repository is continuously updated with new tutorials and examples. Stay tuned and happy learning! 🚀
