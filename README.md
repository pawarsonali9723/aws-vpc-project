# AWS VPC Public & Private Subnet Project

## Overview
Created AWS VPC architecture with public and private subnet.

## Services Used
- VPC
- Public Subnet
- Private Subnet
- Route Table
- Internet Gateway
- EC2

## Steps Performed
1. Created custom VPC
2. Created public subnet
3. Created private subnet
4. Attached Internet Gateway
5. Configured Route Table
6. Associated subnet with route table
7. Enabled auto public IP
8. Launched public EC2 instance
9. Launched private EC2 instance
10. Connected public EC2 using Git Bash
11. Connected private EC2 through Bastion Host

## Output
Successfully connected private EC2 using SSH through public EC2.

## Architecture
Internet Gateway  
↓  
Public Subnet  
↓  
Public EC2 (Bastion Host)  
↓  
Private EC2
