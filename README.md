# Terraform-Web-Server

##  Project Overview
This project provisions a simple **web server on AWS** using **Terraform**.  
It creates a VPC, public subnet, security group, and an EC2 instance with Apache installed via user data.

## Architecture
- **VPC** with a public subnet
- **Internet Gateway** and route table for internet access
- **Security Group** allowing SSH (22) and HTTP (80)
- **EC2 Instance** with Apache web server
- **User Data** installs Apache and deploys a "Hello from Terraform" page

##  How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/terraform-webserver.git
   cd terraform-webserver
