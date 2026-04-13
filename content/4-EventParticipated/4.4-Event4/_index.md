---
title: "Event 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

# Summary Report: “Cloud Mastery Series #3: Security & Networking in AWS”
![event4](picture2.jpeg)
### Event Information

- **Event Name:** Cloud Mastery Series #3: Security & Networking in AWS  
- **Time:** 09:00 – 12:00, April 11, 2026  
- **Location:** FPTU - Hall Academic A  
- **Role:** Attendee  

### Description

The event focused on security solutions for network infrastructure and identity management on the Amazon Web Services (AWS) platform. The content covered setting up multi-layered firewalls, secure access management, and cyber-attack prevention techniques.

### Event Objectives

- Master core network security services: AWS WAF, Shield, and Network Firewall.  
- Understand the operational mechanisms of VPC, Subnet, NACL, and Security Groups.  
- Deploy Identity and Access Management (IAM) according to the highest security standards.

### Speakers

- Lam Tuan Kiet: DevOps Engineer (AWS Security topic).  
- Lam An Thinh & Nguyen Phan Quoc Viet: (Networking on AWS topic).
- Huỳnh Hoàng Long & Đặng Thị Minh Thu: FCAJ Cloud Engineer Ambassadors (IAM topic).

### Highlights

#### Network & Application Protection

- AWS WAF: Protects web applications from common vulnerabilities like SQL Injection and XSS by filtering HTTP/HTTPS traffic. 
- AWS Shield: Provides DDoS protection; the Standard version is free for all customers, while Advanced provides enhanced protection and cost insurance.  
- AWS Network Firewall: A stateful firewall that helps control inbound and outbound traffic at the VPC level.  

#### Networking & VPC Security

- Security Group vs. NACL: 
    - Security Group: Operates at the Instance (ENI) level, stateful (automatically allows return traffic).  
    - NACL: Operates at the Subnet level, stateless, requires configuring both Inbound and Outbound rules. 
- NAT Gateway: Allows resources in a Private Subnet to connect to the Internet (for patching) but prevents reverse connections from the Internet.

#### Identity Management (IAM)

- Principle of Least Privilege: Granting only the exact and sufficient permissions needed for users or services.  
- Service Control Policies (SCPs): Establish maximum permission guardrails for all accounts in an organization (AWS Organizations). 
- Credential Rotation: Encourages the use of IAM Identity Center for short-term credentials instead of long-term Access Keys.  

### Key Takeaways

- Understand how to combine WAF, Shield, and Firewall Manager to create a multi-layered defense system.
- Differentiate between the Stateless mechanism of NACL and the Stateful mechanism of Security Groups to avoid connection errors during network configuration.
- Know how to use IAM Access Analyzer to detect policies that unintentionally expose resources.

### Application to Work

- Apply the Zero Trust model to infrastructure design: always verify and default to denying all connections.
- Use Permission Boundaries to limit permissions for user accounts, preventing privilege escalation within the project.

### Event Experience

The event was very dynamic with practical demos on configuring firewall rules and checking access permissions. The speakers enthusiastically answered questions about common errors such as "Port Exhaustion" on NAT Gateways.

### Lessons Learned

 Misconfiguring a small rule in NACL or exposing a long-term Access Key can lead to significant risks for the entire system. Always prioritize using MFA and centralized management services like Firewall Manager. 

### Event Photos

![event4](picture1.jpeg)

### Conclusion

Cloud Mastery Series #3 provided a comprehensive and in-depth perspective on multi-layered protection in the AWS cloud environment. The content went beyond theory to delve into the practical operational mechanisms of network infrastructure and identity management.
