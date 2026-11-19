# AWS Cloud Infrastructure & Monitoring Project

## Project Overview
Designed and deployed a cloud infrastructure using Amazon Web Services (AWS), including networking, compute, storage, security, and monitoring.

## Technologies Used
- AWS VPC
- Amazon EC2
- AWS IAM
- Security Groups
- Amazon S3
- Amazon CloudWatch
- Amazon SNS
- Amazon Linux 2023
- Linux

## Project Implementation

### 1. VPC
- Created an AWS Virtual Private Cloud.
- Configured networking resources.

### 2. EC2 Instance
- Launched an EC2 instance.
- Connected using EC2 Instance Connect.
- Used Amazon Linux 2023.

### 3. Security & IAM
- Configured security groups.
- Worked with AWS IAM permissions.

### 4. S3 Static Website
- Configured an S3 bucket for static website hosting.

### 5. CloudWatch Monitoring
- Created a CloudWatch CPU utilization alarm.
- Configured a 50% CPU utilization threshold.
- Configured SNS email notifications.
- Installed and used `stress-ng` to simulate high CPU usage.
- Successfully triggered the alarm and received an email notification.

## Project Outcome
Successfully deployed AWS infrastructure and tested automated monitoring and email notifications using CloudWatch and SNS.

## Skills Demonstrated
AWS Cloud | Linux | Networking | EC2 | VPC | S3 | IAM | CloudWatch | SNS | Monitoring

## Project Screenshots

The following screenshots document the AWS deployment and monitoring workflow.

| Area | Screenshot |
|---|---|
| EC2 instance | ![EC2 instance](screenshots/01-ec2-instance.png.png) |
| VPC configuration | ![VPC configuration](screenshots/02-vpc-configuration.png.png) |
| S3 bucket | ![S3 bucket](screenshots/03-s3-bucket.png.png) |
| S3 static website hosting | ![S3 static website hosting](screenshots/04-s3-static-hosting.png.png) |
| S3 bucket policy | ![S3 bucket policy](screenshots/05-s3-bucket-policy.png.png) |
| Live static website | ![Live website](screenshots/06-live-website.png.png) |
| CloudWatch alarm — OK | ![CloudWatch alarm OK](screenshots/07-cloudwatch-alarm-ok.png.png) |
| CloudWatch alarm — ALARM | ![CloudWatch alarm triggered](screenshots/08-cloudwatch-alarm-triggered.png.png) |
| SNS email notification | ![SNS email notification](screenshots/09-sns-email-notification.png.png) |
