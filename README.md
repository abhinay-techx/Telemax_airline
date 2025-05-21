# Real-Time Data Ingestion & Deployment on AWS Project

## 📌 Project Overview

**TELEMAX**, a growing airline management company, is building a cloud-native system to accept real-time data from vendors and store it in a NoSQL database for future analysis. To support its expansion in underserved markets, TELEMAX is seeking a scalable AWS-based solution. This project demonstrates how to design and deploy such an architecture using AWS services.

---

## 🎯 Objective

To build a real-time, scalable data ingestion pipeline using:
- AWS EC2 for hosting
- SQS for message queuing
- Lambda for serverless processing
- DynamoDB for NoSQL storage
- Docker + .NET for containerized application deployment on Amazon ECR

---

## 🛠️ Tasks Breakdown

1. **Create EC2 Instance**
   - Launch a Linux (Ubuntu) instance on AWS.

2. **Set Up SQS Queue**
   - Create and test a Standard SQS Queue with dummy vendor data.

3. **Install Docker on EC2**
   - Set up Docker and verify with a sample container.

4. **Create IAM Role with ECR Access**
   - Define minimal permissions and allow push/pull from ECR.

5. **Attach IAM Role to EC2**
   - Ensure EC2 instance can access ECR securely.

6. **Create DynamoDB Table**
   - Set up table to store real-time vendor data.

7. **Write Lambda Function**
   - Accept SQS messages and store them in DynamoDB.

8. **Connect Lambda to SQS**
   - Trigger Lambda when new messages arrive in the queue.

9. **Deploy .NET App to ECR**
   - Containerize the app using Docker and push it to ECR.

10. **Documentation & Final Presentation**
    - Include all steps, screenshots, and an architecture diagram.

---

## 📚 Learning Outcomes

- Understanding of real-time cloud architectures
- Proficiency in key AWS services (EC2, SQS, Lambda, ECR, IAM, DynamoDB)
- Containerization using Docker and .NET
- Designing decoupled and scalable serverless solutions

---

## 📝 Authors

- Project by: Abhinay Kumar
