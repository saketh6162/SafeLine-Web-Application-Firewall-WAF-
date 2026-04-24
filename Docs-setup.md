# ⚙️ Setup Guide

## Step 1: Environment Setup

* Installed VirtualBox
* Created Ubuntu VM
* Allocated 4GB RAM and 20GB storage

## Step 2: Install Docker

* Installed docker.io and docker-compose
* Verified using `docker ps`

## Step 3: Deploy DVWA

* Created docker-compose.yml
* Ran `docker-compose up -d`
* Accessed DVWA at http://localhost

## Step 4: Install SafeLine WAF

* Ran installation script
* Accessed dashboard at https://localhost:9443

## Step 5: Configure WAF

* Added DVWA as application
* Used reverse proxy mode
* Set correct upstream (Docker container IP)

## Step 6: Enable Protection

* Enabled SQL Injection protection
* Enabled HTTP Flood (rate limiting)
