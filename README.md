# AWS VPC Networking Assignment

## 📌 Project Overview
This project demonstrates the design and implementation of a secure and scalable AWS Virtual Private Cloud (VPC) architecture. The goal was to build a segmented network environment using public and private subnets, routing components, and security controls to replicate a real-world cloud infrastructure setup.

The project focuses on core AWS networking principles including subnet design, routing, internet access control, and network security configuration.

---

## 🎯 Objectives
- Design a custom Virtual Private Cloud (VPC)
- Configure public and private subnets across availability zones
- Implement secure routing using route tables
- Enable controlled internet access using an Internet Gateway
- Secure network traffic using Security Groups
- Configure NAT Gateway for private subnet outbound access

---

## 🏗 Architecture Summary
The architecture consists of:
- A custom VPC with defined CIDR range
- Public subnets for internet-facing resources
- Private subnets for internal-only resources
- Internet Gateway for public connectivity
- Route tables to manage traffic flow
- Security Groups to enforce access control

---

## 🪜 Implementation Steps

### 1. VPC Creation
A custom Virtual Private Cloud (VPC) was created to establish an isolated network environment within AWS.

---

### 2. Subnet Configuration
Public and private subnets were created across multiple Availability Zones to improve availability and separate workloads based on exposure requirements.

---

### 3. Internet Gateway Setup
An Internet Gateway was attached to the VPC to allow resources in public subnets to communicate with the internet.

---

### 4. Route Table Configuration
Route tables were configured to direct internet-bound traffic from public subnets through the Internet Gateway, while private subnets remained isolated.

---

### 5. Security Groups
Security Groups were implemented to control inbound and outbound traffic at the instance level, ensuring only required ports and protocols were allowed.

---

### 6. NAT Gateway 
A NAT Gateway was deployed to allow instances in private subnets to access the internet securely without exposing them to inbound traffic.

---

## 📸 Evidence
Screenshots of each stage of the implementation are included in this repository, demonstrating configuration and setup within the AWS Management Console.

---

## 🧠 Key Learnings
- Understanding of VPC architecture and CIDR design
- How AWS routing tables control network traffic flow
- Difference between public and private subnet behaviour
- Role of Internet Gateway vs NAT Gateway
- Importance of Security Groups in cloud security

---

## 🚀 Outcome
This project successfully demonstrates a functional AWS VPC architecture with segregated network layers, secure routing, and controlled internet access. It reflects foundational cloud networking knowledge applicable to real-world cloud infrastructure design.

---

## 👤 Author
Built as part of an AWS networking assignment demonstrating practical cloud infrastructure skills.
