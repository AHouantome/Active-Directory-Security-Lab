
Active Directory Security Lab (Windows Server 2022)
📌 Project Overview

This project demonstrates the deployment, configuration, and security-focused management of an enterprise Active Directory (AD) environment using Windows Server 2022.
The lab simulates a real-world organizational domain to showcase identity and access management (IAM) concepts, user administration, and foundational security best practices relevant to SOC and cybersecurity roles.

🏗️ Lab Environment

Hypervisor: VMware Workstation

Domain Controller: Windows Server 2022

Domain Name: tomvis.com

Directory Service: Active Directory Domain Services (AD DS)

Client System: Windows 11 (prepared for domain integration)

🎯 Project Objectives

Deploy and configure an Active Directory Domain Controller

Create and manage domain users and security groups

Implement Organizational Units (OUs) for structured administration

Apply role-based access control (RBAC) principles

Build a foundation for authentication monitoring and SOC analysis

🛠️ Implementation Details
1️⃣ Domain Controller Setup

Installed Active Directory Domain Services (AD DS)

Promoted Windows Server 2022 to a Domain Controller

Created a new forest and domain: tomvis.com

📸 Domain Controller Information


2️⃣ Active Directory Domain Structure

Verified Active Directory and DNS integration

Confirmed proper domain hierarchy and components

📸 Active Directory Domain Tree


3️⃣ Domain Users Management

Created multiple domain user accounts

Assigned users based on organizational roles

Prepared environment for authentication and access testing

📸 Domain Users


4️⃣ User Roles & Permissions

Differentiated standard users from privileged accounts

Applied group-based access control for scalability and security

📸 User Role Details


5️⃣ Security Groups Configuration

Utilized built-in and custom security groups

Followed least-privilege principles

Avoided direct user permission assignments

📸 Security Groups


6️⃣ Organizational Units (OUs)

Created Organizational Units to logically separate users and resources

Improved manageability and readiness for Group Policy enforcement

📸 Organizational Units


7️⃣ Domain Controllers OU

Verified Domain Controllers are correctly placed in the dedicated OU

Ensured compliance with AD best practices

📸 Domain Controllers OU


8️⃣ Server Manager & AD Tools

Managed AD roles and services via Server Manager

Used Active Directory Users and Computers (ADUC) for administration

📸 Server Manager – AD DS Installed


🔐 Security Focus & Best Practices

Role-Based Access Control (RBAC)

Separation of administrative and standard user accounts

Group-based permission management

Structured OU design for enterprise scalability

Secure identity management fundamentals

🧠 Skills Demonstrated

Active Directory administration

Identity & Access Management (IAM)

Windows Server 2022 configuration

User and group management

Enterprise security concepts

Technical documentation

🚀 Future Enhancements

Group Policy Object (GPO) hardening

Password and account lockout policies

Authentication log monitoring

SIEM integration (Splunk / Wazuh)

Detection of suspicious login behavior
