---
title: "Integrating Security into CI/CD Pipeline: A DevSecOps Approach"
date: 2024-02-01 # Example date, adjust as needed
draft: false
image: "/images/projects/profilepic.jpeg" # Replace with actual image
technologies: ["AWS EC2", "Jenkins", "SonarQube", "Docker", "Trivy", "OWASP Dependency-Check"]
description: "Implemented a DevSecOps methodology to embed security within the CI/CD pipeline using Jenkins, SonarQube, Trivy, and AWS."
github_link: "https://github.com/Yashank-Sahu/DevSecOps-In-Action.git"
live_url: "" # Add if you have a live demo/presentation
---

## Project Overview
This project implements a DevSecOps methodology to embed security within the CI/CD (Continuous Integration/Continuous Delivery) pipeline. It aims to ensure secure software development by automating security tests at various stages, adhering to DevSecOps best practices.

### Key Features & Functionalities:
* **SCA (Software Composition Analysis):** OWASP Dependency-Check is used to scan open-source libraries for known vulnerabilities.
* **SAST (Static Application Security Testing):** SonarQube analyzes code for security flaws and vulnerabilities prior to deployment.
* **Docker Security:** Trivy scans Docker images for vulnerabilities before they are deployed.
* The pipeline is powered by AWS EC2, utilizing SonarQube for static analysis and Jenkins for CI/CD automation.
* Security checks are automatically performed at every stage to identify problems early, thereby speeding up the delivery of secure software.

## Technical Details
The CI/CD pipeline orchestrated by Jenkins integrates various security tools. On every code commit, Jenkins triggers a build that includes:
1.  Code checkout.
2.  Static analysis using SonarQube to identify code smells and security vulnerabilities.
3.  Dependency checking using OWASP Dependency-Check.
4.  Building a Docker image for the application.
5.  Scanning the Docker image for vulnerabilities using Trivy.
6.  (Conditional) Deployment to a staging/production environment on AWS EC2 if all checks pass.

## Learnings
This project provided hands-on experience in automating security within a DevOps workflow, selecting appropriate security tools for different stages of the SDLC, and configuring CI/CD pipelines for enhanced security posture.