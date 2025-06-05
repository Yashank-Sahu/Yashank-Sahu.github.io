---
title: "Linux Security Log Analyzer"
date: 2023-08-01 # Example date
draft: false
image: "/images/projects/placeholder-loganalyzer.png" # Replace with actual image
technologies: ["Linux", "Python", "GeoIP", "UFW", "iptables", "Snort", "Fail2Ban", "SSL/TLS", "Apache"]
description: "Designed a multi-layered security framework for a Linux-based Apache web application, focusing on log analysis and threat mitigation."
repo_url: "https://github.com/Yashank-Sahu/Your-Repo-Name-Here" # Placeholder: Update with actual repo link
live_url: ""
---

## Project Overview
This project involved designing and developing a multi-layered security framework for a Linux-based Apache web application, employing a defense-in-depth strategy. The main purpose was to secure the network infrastructure, prevent unauthorized access, and mitigate common web application threats, with a component focused on analyzing security logs.

### Key Features & Contributions:
* **Security Framework:**
    * Configuration of robust firewall rules using UFW (Uncomplicated Firewall) and iptables.
    * Implementation of an Intrusion Detection/Prevention System (IDS/IPS) using Snort.
    * Setup of host-level protection mechanisms with Fail2Ban to block malicious IPs based on log analysis.
    * Securing data transmission through SSL/TLS encryption.
    * Hardening the Linux operating system and implementing security best practices to mitigate vulnerabilities like SQL injection and Cross-Site Scripting (XSS).
* **Log Analysis Component (Conceptual - expand as per your actual project):**
    * Developed Python scripts to parse and analyze Apache access/error logs, system logs (syslog, auth.log), and Snort alert logs.
    * Integrated GeoIP lookup to identify the origin of suspicious requests.
    * Designed a system for identifying patterns indicative of brute-force attacks, web scans, or other malicious activities.

## Technical Details
The log analyzer component utilized Python for scripting, leveraging libraries for text processing and regular expressions. It was designed to:
1.  Collect logs from various sources.
2.  Normalize log formats.
3.  Identify suspicious activities based on predefined rules and patterns.
4.  Generate alerts or reports for security personnel.
5.  (Potentially) Feed data into Fail2Ban for automated IP blocking.

## Learnings
This project provided insights into Linux system security, network defense mechanisms, web application vulnerabilities, and the importance of log analysis in identifying and responding to security incidents. It combined system administration, network security, and scripting skills.