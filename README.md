# AWS Production Server Project

## Overview
This project demonstrates the deployment of a live web server on AWS using EC2, Ubuntu Linux, and Nginx.

The goal was to practice real-world cloud administration, Linux commands, web server setup, and public hosting.

---

## Technologies Used

- AWS EC2
- Ubuntu Server
- Linux CLI
- SSH
- Nginx
- Security Groups
- HTML

---

## Project Steps

1. Launched AWS EC2 Ubuntu instance
2. Configured inbound security rules:
   - SSH (Port 22)
   - HTTP (Port 80)
   - HTTPS (Port 443)

3. Connected via SSH using PEM key

4. Updated server packages:

```bash
sudo apt update && sudo apt upgrade -y
installed Nginx: Sudo app install nginx -y
verified service: sudo systemctl status nginx
Replaced default nginx page with custom HTML website
LIVE RESULTS: Custom webpage deployed successfully on public EC2 IP address
AUTHOR-DevOps/cloud Engineering Journey
