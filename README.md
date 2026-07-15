# AWS Web Application Deployment using VPC, EC2, S3, CloudWatch and SNS

## Project Overview

This project demonstrates how to design, deploy, and monitor a web application on Amazon Web Services (AWS) using the AWS Management Console.

The project includes creating a custom Virtual Private Cloud (VPC), configuring networking components, deploying a web server on Amazon EC2, hosting a static website on Amazon S3, monitoring the EC2 instance with Amazon CloudWatch, and configuring Amazon SNS for email notifications.

---

## AWS Services Used

- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- Amazon EC2
- Apache HTTP Server
- Amazon S3 Static Website Hosting
- Amazon CloudWatch
- Amazon SNS

---

## Project Architecture

Internet
↓
Internet Gateway
↓
Custom VPC
↓
Public Subnet
↓
EC2 (Apache Web Server)
↓
CloudWatch Alarm
↓
SNS Email Notification

Separate Service

Amazon S3 Static Website Hosting

---

## Project Steps

1. Created a custom VPC.
2. Created a Public Subnet.
3. Attached an Internet Gateway.
4. Configured a Public Route Table.
5. Associated the subnet with the Route Table.
6. Created a Security Group allowing SSH and HTTP traffic.
7. Launched an Amazon EC2 instance.
8. Connected securely using SSH.
9. Installed Apache HTTP Server.
10. Deployed a sample web application.
11. Configured CloudWatch CPU monitoring.
12. Configured Amazon SNS email notifications.
13. Created an Amazon S3 bucket.
14. Enabled Static Website Hosting.
15. Uploaded the website files.
16. Configured the bucket policy for public access.

---

## Skills Demonstrated

- AWS Networking
- EC2 Administration
- Linux Commands
- Apache Web Server
- Amazon S3
- Cloud Monitoring
- AWS Security
- Static Website Hosting

---

## Screenshots

Project screenshots are available in the **screenshots** folder.

---

## Author

**Anitha**
