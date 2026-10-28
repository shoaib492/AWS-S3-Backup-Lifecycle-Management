# 🚀 Automated S3 Backup & Lifecycle Management System

## 📌 Project Overview
This hands-on AWS project demonstrates secure object storage, data protection, and automated storage cost optimization using Amazon S3 and AWS IAM.

## 🎯 Project Objectives
- Protect objects using S3 Versioning.
- Automate storage lifecycle transitions.
- Apply least-privilege access using IAM.
- Manage backups, documents, and logs securely.

## 🛠️ AWS Services Used
- Amazon S3
- AWS IAM
- S3 Versioning
- S3 Lifecycle Management

## ⚙️ Key Implementations
- Created an S3 bucket with structured storage for documents, backups, and logs.
- Enabled S3 Versioning to help recover from accidental overwrites or deletions.
- Configured lifecycle transitions from S3 Standard to Standard-IA and Glacier Flexible Retrieval.
- Created a dedicated IAM user with controlled S3 access.
- Designed a custom IAM policy following the principle of least privilege.
- Tested object versioning and reviewed lifecycle configurations through the AWS Console.

## 🧠 Key Learnings
- S3 object versioning and recovery
- Lifecycle rules and storage class transitions
- IAM policies and least-privilege access
- Cloud storage security and cost optimization

## 📸 Project Screenshots

### 1. S3 Bucket Objects
![S3 Bucket Objects](01-S3-Bucket-Objects.jpeg)

### 2. S3 Versioning Enabled
![S3 Versioning](02-S3-Versioning-Enabled.jpeg)

### 3. S3 Lifecycle Configuration
![S3 Lifecycle Configuration](03-S3-Lifecycle-Configuration.jpeg)

### 4. IAM Backup Bucket Policy
![IAM Backup Bucket Policy](04-IAM-Backup-Bucket-Policy.jpeg)

### 5. S3 Lifecycle Rule Configuration
![Lifecycle Rule](05-S3-Lifecycle-Rule-Configuration.jpeg)

### 6. IAM S3 Backup Bucket Access Policy
![S3 Access Policy](06-IAM-S3-Backup-Bucket-Access-Policy.jpeg)

### 7. IAM Backup User Permissions
![Backup User Permissions](07-IAM-Backup-User-Permissions.jpeg)

## 🔐 Security Notes
- No AWS access keys, secret keys, or passwords should be committed.
- Lifecycle transitions depend on the configured rules and object eligibility.
- Review IAM permissions before using them in production.

## 👨‍💻 Author
Shoaib Mangalgi

DevOps Trainee | AWS | Linux | Cloud Computing
