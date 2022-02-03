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

Desktop 2 (for daily development and remote access (SSH) to the Linux 'server')
- vendor: Apple
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
 - Introduction to AWS 
 - Create an AWS account 
 - IAM - Manage Users, Roles and Permissions 
 - Regions & Availability Zones 
 - VPC - Manage Private Network on AWS 
 - CIDR Blocks explained 
 - Introduction to EC2 Virtual Cloud Server 
- Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 1 
- Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 2 
 - Deploy to EC2 server from Jenkins Pipeline - CI/CD Part 3 
 - Introduction to AWS CLI 
 - AWS & Terraform Preview 
 - Container Services on AWS Preview 

Week 10 - Container Orchestration with Kubernetes
 - Intro to Kubernetes 
 - Main Kubernetes Components 
 - Kubernetes Architecture 
 - Minikube and kubectl - Local Kubernetes Cluster 
 - Main kubectl commands 
 - YAML Configuration File 
 - Complete Demo Project - Deploying Application in Kubernetes Cluster 
 - Namespaces - Organizing Components 
 - Services - Connecting to Applications inside cluster 
 - Ingress - Connecting to Applications outside cluster 
 - Volumes - Persisting Application Data 
 - ConfigMap & Secret Volume Types 
 - StatefulSet - Deploying Stateful Applications 
 - Managed Kubernetes Services Explained 
 - Helm - Package Manager for Kubernetes 
 - Helm Demo - Managed K8s cluster 
 - Deploying Images in Kubernetes from private Docker repository 
 - Kubernetes Operators for Managing Complex Applications 
 - Helm and Operator Demo 
 - Secure your cluster - Authorization with RBAC 
 - Microservices in Kubernetes 
 - Demo project: Deploy Microservices Application 
 - Production & Security Best Practices 
 - Demo project: Create Helm Chart for Microservices 
 - Demo project: Deploy Microservices with Helmfile 

Week 11 - Kubernetes on AWS - EKS
 - Container Services on AWS 
 - Create EKS cluster with AWS Management Console
 - Configure Autoscaling in EKS cluster 
 - Create Fargate Profile for EKS Cluster 
 - Create EKS cluster with eksctl command line tool 
 - Deploy to EKS Cluster from Jenkins Pipeline 
 - BONUS: Deploy to LKE Cluster from Jenkins Pipeline 
 - Jenkins Credentials Note on Best Practices 
 - Complete CI/CD Pipeline with EKS and DockerHub 
 - Complete CI/CD Pipeline with EKS and ECR 

Week 12 - Infrastructure as Code with Terraform
 - Introduction to Terraform 
- Install Terraform & Setup Terraform Project 
- Providers in Terraform 
- Resources & Data Sources 
- Change & Destroy Terraform Resources 
- Terraform commands
- Terraform State 
 - Output Values 
 - Variables in Terraform 
 - Environment Variables in Terraform 
 - Create Git Repository for local Terraform Project
 - Automate Provisioning EC2 with Terraform - Part 1 
 - Automate Provisioning EC2 with Terraform - Part 2 
 - Automate Provisioning EC2 with Terraform - Part 3 
 - Provisioners in Terraform 
 - Modules in Terraform - Part 1 
 - Modules in Terraform - Part 2 
 - Modules in Terraform - Part 3 
 - Automate Provisioning EKS cluster with Terraform - Part 1 
 - Automate Provisioning EKS cluster with Terraform - Part 2 
 - Automate Provisioning EKS cluster with Terraform - Part 3 
 - Complete CI/CD with Terraform - Part 1
 - Complete CI/CD with Terraform - Part 2 
 - Complete CI/CD with Terraform - Part 3 
 - Remote State in Terraform 

Week 13 - Programming Basics with Python
- Introduction to Python 
 - Installation and Local Setup 
- Our first Python Program 
- Python IDE vs Simple File Editor 
 - Strings and Number Data Types 
- Variables 
- Functions 
- Accepting User Input 
- Conditionals (if / else) and Boolean Data Type 
 - Error Handling with Try-Except 
 - While Loops 
 - Lists and For Loops 
 - Comments 
 - Sets 
 - Built-In Functions 
 - Dictionary Data Type 
 - Modules 
 - Project: Countdown App 
 - Packages, PyPI and pip 
 - Project: Automation with Python (Spreadsheet) 
 - OOP: Classes and Objects 
 - Project: API Request to GitLab 

Week 14 - Automation with Python
 - Introduction to Boto Library (AWS SDK for Python) 
 - Install Boto3 and connect to AWS 
 - Getting familiar with Boto 
 - Terraform vs Python - understand when to use which tool
 - Health Check: EC2 Status Checks 
 - Write a Scheduled Task in Python 
 - Configure Server: Add Environment Tags to EC2 Instances 
 - EKS cluster information 
- Backup EC2 Volumes: Automate creating Snapshots 
 - Automate cleanup of old Snapshots 
 - Automate restoring EC2 Volume from the Backup 
 - Handling Errors 
 - Website Monitoring 1: Scheduled Task to Monitor Application Health 
 - Website Monitoring 2: Automated Email Notification 
 - Website Monitoring 3: Restart Application and Reboot Server 

Week 15 - Configuration Management with Ansible
 - Introduction to Ansible 
 - Install Ansible
 - Setup Managed Server to Configure with Ansible 
 - Ansible Inventory and Ansible ad-hoc commands 
 - Configure AWS EC2 server with Ansible 
 - Managing Host Key Checking and SSH keys 
 - Introduction to Playbooks 
 - Ansible Modules 
 - Collections in Ansible 
 - Project: Deploy Nodejs application - Part 1 
 - Project: Deploy Nodejs application - Part 2 
 - Project: Deploy Nodejs application - Part 3 
 - Ansible Variables - make your Playbook customizable 
 - Project Deploy Nexus - Part 1 
 - Project Deploy Nexus - Part 2 
 - Ansible Configuration - Default Inventory File
 - Project: Run Docker applications - Part 1 
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
