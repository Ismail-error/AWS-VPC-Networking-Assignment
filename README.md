# AWS VPC Networking Assignment

## 📌 Project Overview
This project demonstrates the design and implementation of a secure AWS Virtual Private Cloud (VPC). The architecture includes public and private subnets, routing configuration, and security controls to simulate a real-world cloud networking environment.

---

## 🎯 Objectives
- Create a custom VPC in AWS
- Configure public and private subnets
- Set up an Internet Gateway for external connectivity
- Configure route tables for traffic control
- Apply Security Groups for access restriction
- Implement NAT Gateway for private subnet access

---

## 🏗 Architecture Summary
The architecture consists of:
- Custom VPC with CIDR block
- Public and private subnets across availability zones
- Internet Gateway for public access
- Route tables for traffic control
- Security Groups for instance-level protection

---

## 🪜 Implementation Steps

---

### 1. VPC Creation

![VPC Creation](./1.%20VPC%20Creation.PNG)

A custom Virtual Private Cloud (VPC) was created to establish an isolated network environment within AWS using a defined CIDR block.

---

### 2. Subnet Configuration

![Subnet Configuration](./2.%20Subnet%20Configuration.PNG)

Public and private subnets were configured across multiple Availability Zones to separate internet-facing resources from internal workloads.

---

### 3. Internet Gateway Setup

![Internet Gateway](./3.%20Internet%20Gateway.PNG)

An Internet Gateway was attached to the VPC to enable internet access for resources located in public subnets.

---

### 4. Route Table Configuration

![Route Tables](./4.%20Route%20Tables.PNG)

Route tables were configured to direct public subnet traffic through the Internet Gateway while keeping private subnet traffic isolated.

---

### 5. Security Groups

![Security Groups](./5.%20Security%20Groups.PNG)

Security Groups were implemented to control inbound and outbound traffic at the instance level, allowing only required ports and protocols.

---

### 6. NAT Gateway

![NAT Gateway](./6.%20NAT%20Gateway.PNG)

A NAT Gateway was configured to allow secure outbound internet access for instances in private subnets without exposing them to inbound traffic.

---

## 🧪 Final Result

![Final Architecture](./7.%20Final%20Architecture.PNG)

The completed architecture demonstrates a fully functional AWS VPC with segmented networking, controlled routing, and secure access design.

---

## 🧠 Key Learnings
- VPC design and CIDR planning
- Difference between public and private subnets
- Role of Internet Gateway vs NAT Gateway
- Traffic control using route tables
- Importance of Security Groups in AWS security

---

## 🚀 Outcome
This project demonstrates a foundational understanding of AWS networking and cloud infrastructure design, replicating a secure and scalable production-style VPC environment.

---

## 👤 Author - Ismail
AWS Networking Assignment – Cloud Infrastructure Project
