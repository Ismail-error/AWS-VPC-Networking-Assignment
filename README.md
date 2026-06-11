# AWS VPC Networking Assignment

## 📌 Project Overview
This project demonstrates the design and deployment of a secure and scalable AWS Virtual Private Cloud (VPC). The architecture includes public and private subnets, routing configuration, and network security controls to simulate a real-world cloud infrastructure environment.

---

## 🎯 Objectives
- Design and build a custom VPC in AWS
- Create and configure public and private subnets
- Implement Internet Gateway for external connectivity
- Configure route tables for controlled traffic flow
- Deploy NAT Gateway for secure outbound access from private subnet
- Launch and test EC2 instances in different network tiers
- Apply security best practices for network isolation

---

## 🏗 Architecture Overview
The VPC is structured into:
- Public Subnet: Hosts internet-facing resources (e.g. public EC2 instance)
- Private Subnet: Hosts internal resources with no direct internet access
- Internet Gateway: Enables internet access for public subnet resources
- NAT Gateway: Allows secure outbound internet access for private subnet instances

---

## 🛠 Implementation Steps

### 1. VPC Creation
![VPC Creation](./1.%20vpc-creation.png)

A custom VPC was created using a defined CIDR block to provide an isolated networking environment.

---

### 2. Public Subnet Creation
![Public Subnet Creation](./2.%20Public%20Subnet%20Creation.PNG)

A public subnet was created to host internet-facing resources.

---

### 3. Private Subnet Creation
![Private Subnet Creation](./3.%20Private%20Subnet%20Creation.PNG)

A private subnet was created for internal resources with no direct internet exposure.

---

### 4. Internet Gateway Configuration
![Internet Gateway](./4.%20Internet%20Gateway.PNG)

An Internet Gateway was attached to enable internet connectivity for resources in the public subnet.

---

### 5. Public Route Table Association
![Public Subnet Association](./5.%20Public-Subnet%20Associated.PNG)

Route table configured and associated with the public subnet to allow internet-bound traffic.

---

### 6. NAT Gateway Setup
![NAT Gateway](./6.%20NAT%20Gateway.PNG)

A NAT Gateway was deployed in the public subnet to allow secure outbound internet access for private subnet instances.

---

### 7. Private Route Table Association
![Private Subnet Association](./7.%20Private-Subnet%20Associated.PNG)

The private subnet was associated with a route table directing outbound traffic through the NAT Gateway.

---

### 8. Public EC2 Instance Deployment
![Public EC2 Instance](./8.%20Public-EC2%20Instance%20Details.PNG)

An EC2 instance was launched in the public subnet with internet access enabled.

---

### 9. Public EC2 Instance Verification
![Public EC2 Instance Details](./9.%20Public-EC2%20Instance%20Details.PNG)

Verification of the public EC2 instance configuration and connectivity.

---

### 10. Private EC2 Instance Deployment
![Private EC2 Instance](./10.%20Private-EC2%20Instance%20Details.PNG)

An EC2 instance was launched in the private subnet with restricted access.

---

### 11. Private EC2 Instance Verification
![Private EC2 Instance Details](./11.%20Private-EC2%20Instance%20Details.PNG)

Verification of the private EC2 instance setup.

---

### 12. Private Instance Connectivity Test
![Private Instance Connectivity](./12%20-%20Private%20IP%2C%20Terminal%20Access%2C%20Outbound%20Access.PNG)

Outbound connectivity from the private instance was successfully tested via the NAT Gateway.

---

## 🧠 Key Learnings
- AWS VPC design and network segmentation
- Difference between public and private subnets
- Role of Internet Gateway vs NAT Gateway
- Route table configuration and traffic control
- Secure deployment of EC2 instances in layered architecture

---

## 🚀 Conclusion
This project demonstrates a fully functional AWS VPC architecture with secure segmentation, controlled internet access, and proper routing between public and private subnets. It reflects core cloud networking and security principles.

---

## 👤 Author - Ismail
AWS Networking Assignment – Cloud Infrastructure Project
