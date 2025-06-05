---
title: "DevSecOps Chatbot UI Deployment"
date: 2024-01-01 # Example date
draft: false
image: "/images/projects/placeholder-chatbot.png" # Replace with actual image
technologies: ["Jenkins", "Terraform", "Kubernetes", "AWS"]
description: "Focused on the secure deployment of a Chatbot User Interface using DevSecOps principles and a cloud-native technology stack."
repo_url: "https://github.com/Yashank-Sahu/Your-Repo-Name-Here" # Placeholder: Update with actual repo link
live_url: ""
---

## Project Overview
This project focused on the deployment of a Chatbot User Interface, integrating DevSecOps principles and utilizing a modern cloud-native technology stack on Amazon Web Services (AWS). The goal was to establish a secure, automated, and scalable deployment pipeline for the chatbot application.

*(Yashank, you mentioned you would edit this later. Here are some points you might consider adding for a more complete description:
* What was the specific purpose or problem the chatbot UI addressed?
* What were the key security considerations or DevSecOps practices implemented (e.g., IaC security scanning, container image scanning in the pipeline, secrets management, network policies in Kubernetes)?
* What was your specific role or contribution?
* What were the outcomes or benefits of this DevSecOps approach?)*

## Technical Details
The deployment architecture involved:
* **Infrastructure as Code (IaC):** Terraform was used to define and provision the necessary AWS infrastructure (e.g., EKS cluster, VPC, networking components).
* **CI/CD Pipeline:** Jenkins orchestrated the build, test, and deployment process. This included steps for:
    * Building the chatbot UI application.
    * Containerizing it using Docker.
    * (Ideally) Scanning the Docker image for vulnerabilities.
    * Deploying the application to a Kubernetes cluster (AWS EKS).
* **Kubernetes:** Used for container orchestration, managing scaling, and ensuring high availability of the chatbot UI.

## Learnings
This project provided practical experience in setting up a DevSecOps pipeline for a cloud-native application, working with IaC tools like Terraform, CI/CD with Jenkins, and container orchestration with Kubernetes on AWS. Key focus areas included automating deployment processes while embedding security checks and best practices.