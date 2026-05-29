# Server Setup Documentation

This document provides a complete, reproducible guide for deploying the Azure VM, installing Nginx, configuring the website, and preparing the server environment. Following these steps, another ICT171 student should be able to rebuild the server in under an hour.


## 1. Azure VM Deployment

### Create the Virtual Machine
Azure Portal → Virtual Machines → Create VM

Configuration:
- **Image:** Ubuntu Server 22.04 LTS  
- **Size:** Standard B1s  
- **Authentication:** Password  
- **Inbound ports:** SSH (22), HTTP (80)  
- **Networking:** Assign public IP  

Create the VM and wait for provisioning to complete.


## 2. Connect to the Server

### SSH into the VM
ssh <username>@<public_ip>

## 3. Website Deployment

### Navigate to the web root
cd /var/www/html

### Create custom homepage
sudo nano index.html

### Create directory for review pages
sudo mkdir reviews

### Add individual review pages
sudo nano reviews/<movie>.html

Pages included:
- inception.html  
- phantom-thread.html  
- parasite.html  
- project-hail-mary.html  
- superman-2025.html  

## 3. DNS configuration

### Add A Record
In GoDaddy → Domain → **Manage DNS**


Your site will now load with HTTPS.


## 4. Scripting Component

### Create scripts directory

### Create backup script

### Make executable

### Run script








