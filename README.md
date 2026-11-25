# Project 02: Host a Static Website on Amazon S3 using Terraform

## Overview
This project prepares Terraform infrastructure code for hosting a static website on Amazon S3.

## Objectives
- Prepare Terraform configuration for an S3 bucket.
- Configure static website hosting.
- Define the required website files and outputs.
- Test the website locally.

## Technologies
- AWS S3
- Terraform
- HTML
- Python HTTP Server

## Project Files
- `main.tf` – S3 infrastructure configuration.
- `versions.tf` – Terraform and provider requirements.
- `outputs.tf` – Terraform outputs.
- `index.html` – Static website homepage.
- `.gitignore` – Files excluded from version control.

## Local Website Testing
The website was tested locally using Python's HTTP server.

Command:
```powershell
python -m http.server 8001
```

Local URL:
`http://localhost:8001`

**Result:** The website opened successfully in the browser.

## Deployment Status
Terraform configuration has been prepared. The local website test was successful.

**AWS S3 deployment is pending.** No AWS resources were created as part of this local test.

## Learning Outcomes
- Understanding static website hosting.
- Preparing Terraform configuration for Amazon S3.
- Testing HTML websites locally.
- Understanding the difference between local testing and cloud deployment.