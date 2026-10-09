# AdescoTechHub Academy Student Portal

## AWS EC2 and Amazon EBS Deployment Project

**Project by:** Angel

## Project Overview

This project demonstrates the deployment of the AdescoTechHub Academy Student Portal using Amazon Web Services (AWS). The project focused on launching an Ubuntu EC2 instance, deploying a web page using Apache through EC2 User Data, attaching an Amazon Elastic Block Store (EBS) volume, and creating an EBS snapshot for backup purposes.

## Project Objectives

- Launch and configure an Ubuntu EC2 instance.
- Verify the EC2 instance details and running state.
- Automate Apache web server installation using EC2 User Data.
- Deploy and access the Student Portal.
- Create and attach a 10 GiB SSD EBS volume to the EC2 instance.
- Create an EBS snapshot for backup and recovery purposes.

## AWS Services and Technologies Used

| Service or Technology | Purpose |
|---|---|
| Amazon EC2 | Provides the virtual server for hosting the Student Portal. |
| Ubuntu Server | Operating system running on the EC2 instance. |
| Apache Web Server | Serves the Student Portal web page. |
| Amazon EBS | Provides block storage attached to the EC2 instance. |
| EBS Snapshot | Provides a backup of the EBS volume. |
| EC2 User Data | Automates server updates and Apache installation during instance launch. |
| Security Groups | Control network traffic to and from the EC2 instance. |

## Project Implementation

### 1. Launch Ubuntu EC2 Instance
Launched an Ubuntu EC2 instance named `AdescoTechHubAcademy` using the `t3.micro` instance type and created a key pair for secure server access.

### 2. Verify EC2 Instance Details
Confirmed the instance ID, Ubuntu AMI, instance type, public IPv4 address, and running state.

### 3. Deploy the Student Portal Using EC2 User Data
Used an EC2 User Data script to update Ubuntu, install Apache, and start the Apache service. After deployment, accessed the Student Portal.

### 4. Create and Attach an EBS Volume
Created a 10 GiB SSD EBS volume in the same Availability Zone as the EC2 instance (`eu-north-1a`) and attached it to the instance.

### 5. Create an EBS Snapshot
Created an EBS snapshot to provide a backup that could be used to restore the volume if necessary.

## Challenges Encountered

- Understanding the differences between EC2, EBS, and EBS snapshots.
- Learning how to configure security groups correctly.
- Understanding the purpose of EC2 User Data.
- Attaching the EBS volume to the EC2 instance.

## Skills Demonstrated

- AWS Management Console navigation.
- EC2 instance provisioning and configuration.
- Ubuntu server deployment.
- Apache web server setup.
- EC2 User Data automation.
- EBS volume management.
- EBS snapshot creation.
- Basic AWS networking and security concepts.

## Project Documentation

The `ANGEL_AWS_EC2INSTANCE_UBUNTU.docx` file in this repository contains the project report and screenshots documenting the implementation steps.

## Conclusion

This project provided practical experience with AWS compute, storage, basic automation, and backup concepts through the deployment of the AdescoTechHub Academy Student Portal.

**Project status:** Completed as a hands-on AWS training assignment.
