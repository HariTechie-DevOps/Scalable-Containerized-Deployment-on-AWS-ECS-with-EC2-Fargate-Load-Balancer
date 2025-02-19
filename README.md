# Scalable-Containerized-Deployment-on-AWS-ECS-with-EC2-Fargate-Load-Balancer
Designed and deployed a secure, highly available, and scalable on AWS using Amazon ECS with EC2, Docker, Amazon ECR, Fargate, and an Application Load Balancer. The deployment includes a containerized application hosted on ECS, ensuring automated scaling, high availability, and cost efficiency.

# 📌 AWS ECS Deployment with EC2, Docker, ECR, Fargate & Load Balancer

# 🚀 Overview

This project demonstrates how to deploy a containerized application on AWS ECS using EC2 launch type while integrating services like:
✅ Amazon Elastic Container Registry (ECR) – To store Docker images.
✅ Amazon ECS (Elastic Container Service) – To manage and deploy containers.
✅ EC2 Instances – To run ECS tasks with an autoscaling group.
✅ AWS Fargate – For serverless container deployment.
✅ Application Load Balancer (ALB) – For traffic distribution.
✅ Amazon CloudWatch – For monitoring and logging.

The architecture ensures scalability, high availability, and cost efficiency by leveraging AWS-native services.

# 📸 Architecture Diagram

# High-Level Flow:

1️⃣ Develop & Containerize the App: Build a Dockerized web application.

2️⃣ Push Image to Amazon ECR: Store the container image in a private repository.

3️⃣ Deploy to Amazon ECS (EC2 Launch Type): Run the container on an EC2-backed ECS cluster.

4️⃣ Configure an ALB: Distribute incoming requests across ECS tasks.

5️⃣ Enable Auto Scaling: Ensure high availability and scalability with Auto Scaling Groups.

6️⃣ Deploy with AWS Fargate (Optional): For a fully managed, serverless container deployment.
