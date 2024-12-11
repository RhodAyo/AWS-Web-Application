# AWS Web Application

## Project Goal:
This project aims to design and deploy a reliable web application infrastructure on AWS for the company, SmartShop. In developing the solution to meet SmartShop's requirements, some AWS services such as EC2, Virtual Private Cloud (VPC), Identity and Access Management (IAM), Security Groups, etc were used.

## Technologies used:
 - AWS Amazon console
 - GitHub
 - Git Bash
 - Apache Server
 - Web Browser ( Chrome)

## Steps involved in designing and deployment of Web Application Infrastructure:
   Before launching an EC2 instance, you will need to set up your VPC, Subnets, Internet Gateway where you also are able to configure the Route Table, Network Access Control List (NACL).

### Creation of a VPC
- In the AWS Console, the very first thing is to select the region you want to work in, this would determine where all your resources would be both created and deployed from. The region I chose for this project was **'N. Virginia us-east-1'**
![N.Virginia LOcation](images/north_virginia_location.png)

-   Go to VPC > Your VPCs > Create VPC in the AWS Console.
o Name the VPC, choose IPv4 CIDR block (e.g., 10.0.0.0/16), and click Create.
