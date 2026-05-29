# Movie Review Website – Cloud Server Project
Student 33747568

## 1. Overview
This project implements a cloud-hosted movie review website deployed on an Azure Ubuntu Server using Infrastructure-as-a-Service (IaaS). The server is manually configured using Linux command-line tools and custom HTML pages.

**Public IP: 20.213.10.100**


This documentation provides all steps required to recreate the server from scratch.

## 2. Architecture Summary
- Azure Virtual Machine (Ubuntu 22.04 LTS)
- Static HTML website (multi-page)
- Manual configuration (no pre-built images)
- SSH access for administration


## 3. Project Features
- Fully deployed cloud server using Azure IaaS  
- Multi‑page movie review website  
- Custom HTML and CSS  
- Organised directory structure (/var/www/html/reviews/)  
- Professional documentation and reproducibility focus  


## 4. Technologies Used
- **Azure** (Virtual Machine, networking, public IP)
- **Ubuntu Server 22.04 LTS**
- **SSH** (remote administration)
- **HTML/CSS** (website content)
- **GitHub** (documentation + version control)


## 5. Deployment Summary
The server was deployed using the Azure Portal and configured via SSH. The website consists of a homepage and five individual movie review pages.

Full technical steps are documented in:  
**docs/server-setup.md**


## 6. Troubleshooting Log
A record of issues encountered and solutions applied during development.

- Resetting SSH password using Azure “Reset Password”
- Correcting file permissions after creating new directories


## 7. Future Improvements
- Add external CSS stylesheet  
- Add navigation bar  
- Add backend (Python/Node)  
- Add database for dynamic reviews  
- Implement CI/CD pipeline  
- Add HTTPS enforcement  
