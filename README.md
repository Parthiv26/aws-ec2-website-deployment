# aws-ec2-website-deployment
Deploying and hosting a static website on an Ubuntu Linux server using Amazon EC2, Nginx, SSH and AWS Security Groups. AWS EC2 Ubuntu Linux Nginx SSH

# Website Deployment on Amazon EC2

## Project Overview

This project demonstrates how to launch and configure an Amazon EC2 virtual server to host a static website using Ubuntu Linux and the Nginx web server.

The project covers cloud infrastructure deployment, secure remote server access, Linux administration, web server configuration and network security using AWS Security Groups.

## Objectives

- Launch and configure an Amazon EC2 instance.
- Connect securely to a remote Linux server using SSH and key-pair authentication.
- Install and configure the Nginx web server.
- Deploy website files to an EC2 instance.
- Configure AWS Security Groups to control network traffic.
- Understand cloud computing, Linux server management and firewall rules.

## Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2
- Ubuntu Server 24.04 LTS
- Nginx Web Server
- Secure Shell (SSH)
- Secure Copy Protocol (SCP)
- HTML and CSS
- AWS Security Groups
- Windows PowerShell

## Project Implementation

### 1. EC2 Instance Configuration
- Created an Amazon EC2 virtual machine.
- Selected Ubuntu Server 24.04 LTS.
- Configured instance settings and storage.
- Generated an SSH key pair for secure access.

### 2. SSH Remote Connection
- Connected to the Ubuntu server using SSH.
- Used private key authentication.
- Managed the remote Linux environment through the terminal.

### 3. Nginx Installation
- Updated Ubuntu packages.
- Installed the Nginx web server.
- Started and enabled the Nginx service.
- Verified the service status.

### 4. Website Deployment
- Created a custom HTML website.
- Transferred website files using SCP.
- Deployed the website to `/var/www/html/`.
- Tested the web server using HTTP.

### 5. Network Security Configuration
- Configured AWS Security Group inbound rules.
- Used port 22 for SSH access.
- Used port 80 for HTTP traffic.
- Explored port 443 for HTTPS connectivity.

## Architecture

User Browser → AWS Security Group → Amazon EC2 → Ubuntu Linux → Nginx → Website Files

## Security Considerations

- Restricted SSH access to the administrator's IP address.
- Used SSH key-pair authentication.
- Configured inbound network traffic using Security Groups.
- Applied appropriate Linux file permissions.
- Explored secure HTTPS deployment.

## Project Structure

```text
aws-ec2-website-deployment/
│
├── index.html
├── README.md
│
└── screenshots/
    ├── ec2-instance.png
    ├── ssh-connection.png
    ├── nginx-status.png
    ├── security-group.png
    └── live-website.png
```

## Skills Developed

- Cloud Infrastructure Management
- Linux System Administration
- SSH Authentication
- Web Server Configuration
- Network Security
- Firewall Configuration
- Cloud Website Deployment
- Troubleshooting

## Learning Outcomes

Through this project, I gained practical experience in deploying a website on a cloud-based Linux server, configuring a production web server and managing network access through AWS Security Groups.

This project strengthened my understanding of cloud infrastructure, server administration and fundamental cloud security concepts.

## Future Improvements

- Configure HTTPS using Let's Encrypt.
- Connect a custom domain name.
- Implement automated deployment.
- Explore AWS monitoring and logging.
- Strengthen server security configurations.

## Author

Parthiv Patel

Cyber Security | Cloud Security | AWS | Linux
