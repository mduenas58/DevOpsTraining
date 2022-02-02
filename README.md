# DevOpsTraining
### Introduction 
> The objective of this repository is to document the progress and put in practice all the concepts learned in the DevOps Bootcamp I am currently enrolled. 
> [DevOps Bootcamp from TechWorld](https://www.techworld-with-nana.com/devops-bootcamp). 
> The recommended schedule to completion is 6 months, 10-15 hours/week. Currently I am dedicating ~40 hours/week, trying to be more comprehensive on all sujects. Bootcamp ETC is end of April 2022
***
#### Personal hardware/software Setup:
Laptop 1 (simulating a Linux server -Git local repository- and remote access)
- vendor: LENOVO
- version: ThinkPad T420
- product: Intel(R) Core(TM) i5-2520M CPU @ 2.50GHz
- vendor: Intel Corp.
- memory: 16GB 1333 MHz DDR3
- OS: Ubuntu 20.04.1

Desktop 2
- vendor: Apple (for daily development and remote access (SSH) to the Linux 'server')
- version: iMac (21.5-inch)
- Processor: 2.7 GHz Quad-core Intel Core i5
- Memory: 8GB 1600 MHz DDR3
- OS: MacOS Catalina v. 10.15.7
***
### Curriculum - [Techworld DevOps Bootcamp](https://www.techworld-with-nana.com/devops-bootcamp).
Week 1 - Introduction to DevOps
 - Introduction to DevOps

Week 2 - Operating Systems & Linux Basics
 - Introduction to Operating Systems
 - Introduction to Virtualization & Virtual Machines
 - Setup a Linux Virtual Machine
 - Linux File System
 - Introduction to Command Line Interface (CLI - Part 1)
 - Basic Linux Commands (CLI - Part 2)
 - Package Manager - Installing Software on Linux
 - Working with Vim Editor
 - Linux Accounts & Groups (Users & Permissions Part 1)
 - File Ownership & Permissions (Users & Permissions - Part 2)
 - Basic Linux Commands - Pipes & Redirects (CLI - Part 3)
 - Introduction to Shell Scripting Part 1
 - Shell Scripting Part 2 - Concepts & Syntax
 - Shell Scripting Part 3 - Concepts & Syntax
 - Environment Variables
 - Networking
 - SSH - Secure Shell

Week 3 - Version Control with Git
 - Introduction to Version Control and Git
 - Basic Concepts of Git
 - Setup Git Repository Remote and Local
 - Working with Git
 - Initialize a Git project locally
 - Concept of Branches
 - Merge Requests
 - Deleting Branches
 - Rebase
 - Resolving Merge Conflicts
 - Gitignore
 - Git stash
 - Going back in history
 - Undoing commits
 - Merging branches
 - Git for Devops
 
 Week 4 - Build Tools and Package Manager Tools
 - Install Build Tools
 - Installation Help for Windows User - Part 1
- Installation Help for Windows User - Part 2
- Installation Help for MacOS-Unix User
- Build an Artifact
- Build Tools for Development
- Run the Application
 - Build JS Applications
 - Common Concepts and Differences of Build Tools
 - Publish an Artifact
 - Build Tools & Docker
 - Build Tools for DevOps

Week 5 - Cloud & Infrastructure as Service Basics with DigitalOcean
 - Intro to Cloud & IaaS
 - Setup Server on DigitalOcean
 - Deploy and run application artifact on Droplet
 - Create and configure a Linux user on a cloud server

Week 6 - Artifact Repository Manager with Nexus
- Intro to Artifact Repository Manager
- Install and Run Nexus on a cloud server
 - Introduction to Nexus
 - Repository Types
 - Publish Artifact to Repository
 - Nexus REST API
 - Blob Store
 - Component vs Asset
 - Cleanup Policies and Scheduled Tasks

Week 7 - Containers with Docker
- What is a Container
- Container vs Image
- Docker vs. Virtual Machine
 - Docker Architecture and components
- Main Docker Commands
- Debug Commands
 - Docker Demo - Project Overview
 - Developing with Docker
- Docker Compose - Run multiple Docker containers
 - Dockerfile - Build your own Docker Image
 - Private Docker Repository
 - Deploy docker application on a server
 - Docker Volumes - Persisting Data
 - Docker Volumes Demo
 - Create Docker Hosted Repository on Nexus
 - Deploy Nexus as Docker Container

Week 8 - Build Automation & CI/CD with Jenkins

- Intro to Build Automation
- Install Jenkins
- Introduction to Jenkins UI
- Install Build Tools in Jenkins
- Jenkins Basics Demo - Freestyle Job
- Docker in Jenkins
- Freestyle to Pipeline Job
- Intro to Pipeline Job
- Jenkinsfile Syntax
 - Create complete Pipeline
 - Intro to Multibranch Pipeline
 - Jenkins Jobs Overview
 - Credentials in Jenkins
 - Jenkins Shared Library
 - Webhooks - Trigger Pipeline Jobs automatically
 - Dynamically Increment Application version in Jenkins Pipeline - Part 1
 - Dynamically Increment Application version in Jenkins Pipeline - Part 2

Week 9 - AWS Services
 - Introduction to AWS (6:06)
 - Create an AWS account (2:55)
 - IAM - Manage Users, Roles and Permissions (16:05)
 - Regions & Availability Zones (4:38)
 - VPC - Manage Private Network on AWS (12:44)
 - CIDR Blocks explained (6:43)
 - Introduction to EC2 Virtual Cloud Server (35:08)
- Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 1 (26:28)
- Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 2 (28:03)
 - Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 3 (8:39)
 - Introduction to AWS CLI (61:00)
 - AWS & Terraform Preview (2:39)
 - Container Services on AWS Preview (1:23)

Week 10 - Container Orchestration with Kubernetes
 - Intro to Kubernetes (2:49)
 - Main Kubernetes Components (17:29)
 - Kubernetes Architecture (12:38)
 - Minikube and kubectl - Local Kubernetes Cluster (9:39)
 - Main kubectl commands (17:01)
 - YAML Configuration File (14:13)
 - Complete Demo Project - Deploying Application in Kubernetes Cluster (29:35)
 - Namespaces - Organizing Components (15:35)
 - Services - Connecting to Applications inside cluster (23:05)
 - Ingress - Connecting to Applications outside cluster (22:27)
 - Volumes - Persisting Application Data (20:26)
 - ConfigMap & Secret Volume Types (16:26)
 - StatefulSet - Deploying Stateful Applications (15:09)
 - Managed Kubernetes Services Explained (14:45)
 - Helm - Package Manager for Kubernetes (13:44)
 - Helm Demo - Managed K8s cluster (29:17)
 - Deploying Images in Kubernetes from private Docker repository (21:18)
 - Kubernetes Operators for Managing Complex Applications (9:39)
 - Helm and Operator Demo (24:36)
 - Secure your cluster - Authorization with RBAC (15:45)
 - Microservices in Kubernetes (7:04)
 - Demo project: Deploy Microservices Application (35:01)
 - Production & Security Best Practices (35:09)
 - Demo project: Create Helm Chart for Microservices (44:04)
 - Demo project: Deploy Microservices with Helmfile (16:19)

Week 11 - Kubernetes on AWS - EKS
 - Container Services on AWS (28:15)
 - Create EKS cluster with AWS Management Console (55:51)
 - Configure Autoscaling in EKS cluster (35:08)
 - Create Fargate Profile for EKS Cluster (25:47)
 - Create EKS cluster with eksctl command line tool (17:17)
 - Deploy to EKS Cluster from Jenkins Pipeline (26:09)
 - BONUS: Deploy to LKE Cluster from Jenkins Pipeline (14:15)
 - Jenkins Credentials Note on Best Practices (2:36)
 - Complete CI/CD Pipeline with EKS and DockerHub (22:35)
 - Complete CI/CD Pipeline with EKS and ECR (19:08)

Week 12 - Infrastructure as Code with Terraform
 - Introduction to Terraform (18:26)
- Install Terraform & Setup Terraform Project (3:46)
- Providers in Terraform (16:39)
- Resources & Data Sources (23:40)
- Change & Destroy Terraform Resources (9:49)
- Terraform commands (4:10)
- Terraform State (8:31)
 - Output Values (5:05)
 - Variables in Terraform (22:38)
 - Environment Variables in Terraform (9:57)
 - Create Git Repository for local Terraform Project (6:43)
 - Automate Provisioning EC2 with Terraform - Part 1 (51:22)
 - Automate Provisioning EC2 with Terraform - Part 2 (44:21)
 - Automate Provisioning EC2 with Terraform - Part 3 (17:09)
 - Provisioners in Terraform (21:37)
 - Modules in Terraform - Part 1 (9:20)
 - Modules in Terraform - Part 2 (30:09)
 - Modules in Terraform - Part 3 (21:25)
 - Automate Provisioning EKS cluster with Terraform - Part 1 (30:33)
 - Automate Provisioning EKS cluster with Terraform - Part 2 (24:38)
 - Automate Provisioning EKS cluster with Terraform - Part 3 (16:50)
 - Complete CI/CD with Terraform - Part 1 (6:09)
 - Complete CI/CD with Terraform - Part 2 (32:24)
 - Complete CI/CD with Terraform - Part 3 (21:12)
 - Remote State in Terraform (10:22)

Week 13 - Programming Basics with Python
- Introduction to Python (7:08)
 - Installation and Local Setup (6:12)
- Our first Python Program (1:23)
- Python IDE vs Simple File Editor (3:29)
 - Strings and Number Data Types (11:06)
- Variables (9:21)
- Functions (20:17)
- Accepting User Input (15:38)
- Conditionals (if / else) and Boolean Data Type (28:49)
 - Error Handling with Try-Except (5:53)
 - While Loops (12:32)
 - Lists and For Loops (19:08)
 - Comments (4:06)
 - Sets (11:07)
 - Built-In Functions (5:54)
 - Dictionary Data Type (17:07)
 - Modules (18:37)
 - Project: Countdown App (20:18)
 - Packages, PyPI and pip (9:43)
 - Project: Automation with Python (Spreadsheet) (49:55)
 - OOP: Classes and Objects (30:33)
 - Project: API Request to GitLab (15:47)

Week 14 - Automation with Python
 - Introduction to Boto Library (AWS SDK for Python) (2:38)
 - Install Boto3 and connect to AWS (3:02)
 - Getting familiar with Boto (28:54)
 - Terraform vs Python - understand when to use which tool (9:11)
 - Health Check: EC2 Status Checks (25:39)
 - Write a Scheduled Task in Python (9:28)
 - Configure Server: Add Environment Tags to EC2 Instances (14:19)
 - EKS cluster information (13:20)
- Backup EC2 Volumes: Automate creating Snapshots (20:17)
 - Automate cleanup of old Snapshots (23:30)
 - Automate restoring EC2 Volume from the Backup (21:56)
 - Handling Errors (4:08)
 - Website Monitoring 1: Scheduled Task to Monitor Application Health (14:57)
 - Website Monitoring 2: Automated Email Notification (32:34)
 - Website Monitoring 3: Restart Application and Reboot Server (35:22)

Week 15 - Configuration Management with Ansible
 - Introduction to Ansible (15:46)
 - Install Ansible (3:25)
 - Setup Managed Server to Configure with Ansible (2:37)
 - Ansible Inventory and Ansible ad-hoc commands (11:10)
 - Configure AWS EC2 server with Ansible (7:52)
 - Managing Host Key Checking and SSH keys (15:16)
 - Introduction to Playbooks (16:31)
 - Ansible Modules (5:28)
 - Collections in Ansible (11:37)
 - Project: Deploy Nodejs application - Part 1 (17:46)
 - Project: Deploy Nodejs application - Part 2 (17:42)
 - Project: Deploy Nodejs application - Part 3 (7:28)
 - Ansible Variables - make your Playbook customizable (19:28)
 - Project Deploy Nexus - Part 1 (28:31)
 - Project Deploy Nexus - Part 2 (28:02)
 - Ansible Configuration - Default Inventory File (3:27)
 - Project: Run Docker applications - Part 1 (38:13)
 - Project: Run Docker applications - Part 2
 - Project: Terraform & Ansible
 - Dynamic Inventory for EC2 Servers
 - Project: Deploying Application in K8s
 - Project: Run Ansible from Jenkins Pipeline - Part 1
 - Project: Run Ansible from Jenkins Pipeline - Part 2
 - Project: Run Ansible from Jenkins Pipeline - Part 3
 - Ansible Roles - Make your Ansible content more reusable and modular

Week 16 - Monitoring with Prometheus
- Introduction to Monitoring with Prometheus
- Install Prometheus Stack in Kubernetes
- Data Visualization with Prometheus UI
- Introduction to Grafana
- Alert Rules in Prometheus
- Create own Alert Rules - Part 1
- Create own Alert Rules - Part 2
- Create own Alert Rules - Part 3
- Introduction to Alertmanager
- Configure Alertmanager with Email Receiver
- Trigger Alerts for Email Receiver
- Monitor Third-Party Applications
- Deploy Redis Exporter
- Alert Rules & Grafana Dashboard for Redis
- Collect & Expose Metrics with Prometheus Client Library (Monitor own App - Part 1)
- Scrape Own Application Metrics & Configure Own Grafana Dashboard (Monitor own App - Part 2)
***
