# Movie Review Website – Cloud Server Project

## 1. Overview
This project implements a cloud-hosted movie review website deployed on an Azure Ubuntu Server using Infrastructure-as-a-Service (IaaS). The server is manually configured using Linux command-line tools, Nginx, and custom HTML pages.

**Public IP: 20.213.10.100**
**Domain Name:**  
**GitHub Repository:** (this page)

This documentation provides all steps required to recreate the server from scratch.

## 2. Architecture Summary
- Azure Virtual Machine (Ubuntu 22.04 LTS)
- Static HTML website (multi-page)
- Manual configuration (no pre-built images)
- SSH access for administration


## 3. Azure VM Deployment

### 3.1 Create the VM
- Image: Ubuntu Server 22.04 LTS  
- Size: Standard B1s  
- Authentication: Password  
- Inbound ports: SSH (22), HTTP (80)

### 3.2 Connect via SSH

If password is lost, use Azure → VM → Reset Password.

## 4. Initial Server Setup


## 5. Website Deployment

### 5.1 Navigate to web root

### 5.3 Add custom homepage
Your `index.html` contains links to all movie review pages
