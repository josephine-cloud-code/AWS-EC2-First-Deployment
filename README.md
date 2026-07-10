# AWS EC2 First Deployment 

## My First Step Into Cloud Computing

Welcome to my first hands-on cloud project!

As part of my **Cloud Build With Peers learning journey**, I created and deployed my first virtual server using **Amazon Web Services (AWS) EC2**.

This project was my introduction to working with cloud infrastructure. My goal was to move beyond theory and gain practical experience by launching a server, configuring secure access, automating setup, and hosting a simple webpage.

---

## Project Overview

In this project, I explored the basic building blocks of cloud computing:

* Creating a virtual machine in the cloud
* Configuring network and security settings
* Automating server setup using User Data
* Hosting a simple webpage using an Apache web server

This experience helped me understand how cloud engineers provision and manage resources in real-world environments.

---

## Cloud Service Used

### Amazon Web Services (AWS)

**Service:** Amazon Elastic Compute Cloud (EC2)

Amazon EC2 provides scalable virtual servers that allow users to run applications and services in the cloud without managing physical hardware.

---

## Deployment Details

| Component        | Configuration             |
| ---------------- | ------------------------- |
| Cloud Provider   | Amazon Web Services (AWS) |
| Service          | Amazon EC2                |
| Instance Type    | t3.micro                  |
| Operating System | Amazon Linux 2023         |
| Storage          | 8 GiB EBS Volume          |
| Web Server       | Apache (httpd)            |
| Deployment Type  | Beginner Cloud Lab        |

---

Setting Up Security Access 

One of the important lessons I learned during this deployment was that cloud resources must be properly secured.

I configured an EC2 Security Group to control who could access my server.

## SSH Access (Port 22)

Used for secure remote administration.

Configuration:

* Access restricted to my IP address only.
* Allowed me to securely connect and manage the server.

## HTTP Access (Port 80)

Used to make my webpage accessible through a browser.

Configuration:

* Enabled public web access.
* Allowed users to view the hosted webpage.

---

## Automating Server Setup with User Data 

Instead of manually configuring the server after launch, I used an EC2 **User Data script** to automate the setup process.

The script automatically:

✅ Installed the Apache web server (httpd)
✅ Created a simple webpage
✅ Started the Apache service

This introduced me to the importance of automation in cloud environments and how it helps reduce repetitive manual tasks.

---

## My Deployment Process

The steps I completed were:

✅ Created and configured my AWS environment
✅ Launched my first EC2 instance
✅ Selected Amazon Linux 2023 as the operating system
✅ Configured security group rules
✅ Attached cloud storage
✅ Automated server configuration using User Data
✅ Successfully deployed a working webpage

## Key Lessons Learned 

Through this project, I gained practical understanding of:

* How cloud providers deliver computing resources on demand.
* How EC2 allows users to create virtual servers.
* The role of security groups as cloud firewalls.
* How compute, storage, and networking work together.
* How automation improves efficiency in cloud deployments.

Most importantly, I learned that cloud computing is not just about understanding concepts — it is about building, testing, and solving problems in real environments.

## Challenges & Takeaways

During this first deployment, I learned the importance of:

* Carefully managing security settings before exposing services publicly.
* Understanding network access rules.
* Following cloud best practices when configuring resources.

Every step helped me build confidence working with cloud technologies.

## What's Next in My Cloud Journey 

As I continue developing my cloud skills, I plan to explore:

* AWS networking concepts (VPCs and subnets)
* Cloud monitoring and logging
* Infrastructure automation
* Deploying more advanced applications
* Additional AWS services

## Project Evidence

This repository includes:

EC2 instance running successfully
Security group configuration
Deployed webpage
User Data automation script

## Learning Journey

**Program:** Cloud Build With Peers
**Project:** AWS EC2 First Deployment
**Level:** Beginner Cloud Computing Project

---

Thank you for visiting my first cloud project. This is the beginning of my journey into building practical cloud solutions. 
