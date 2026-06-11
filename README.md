# Active Directory User and Group Management Lab

## Project Overview

This lab demonstrates the deployment and administration of Active Directory Domain Services (AD DS) using Windows Server 2022 in a VirtualBox environment.

The objective was to install Active Directory, create a new domain, configure user accounts and security groups, and verify group membership assignments using Active Directory Users and Computers (ADUC).

---

## Technologies Used

* Windows Server 2022
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers (ADUC)
* VirtualBox
* Windows Administration Tools

---

## Lab Objectives

* Install Windows Server 2022
* Deploy Active Directory Domain Services
* Create a new forest and domain
* Configure user accounts
* Create security groups
* Assign users to groups
* Verify Active Directory functionality

---

## Installation Process

### 1. Windows Server Installation

Selected Windows Server 2022 Standard Evaluation (Desktop Experience).

![Windows Server Installation](Screenshots/01-Installation-Type.png)

![Windows Server Edition Selection](Screenshots/02-Windows-Server-Edition-Selection.png)

![Disk Selection](Screenshots/03-Disk-Selection.png)

---

### 2. Active Directory Domain Services Installation

Installed the AD DS role and required management tools.

![AD DS Required Features](Screenshots/04-ADDS-Required-Features.png)

![AD DS Installation Progress](Screenshots/05-ADDS-Installation-Progress.png)

---

### 3. Domain Configuration

Created a new Active Directory forest and configured the root domain.

**Domain Name:** `lab.local`

![Domain Deployment Configuration](Screenshots/06-Domain-Deployment-Configuration.png)

---

## User Management

Created several user accounts to simulate a small business environment.

### IT Administrator Account

* Username: ITAdmin

![Create IT Admin User](Screenshots/07-Create-ITAdmin-User.png)

### Help Desk Account

* Username: HelpDesk

![Create Help Desk User](Screenshots/08-Create-HelpDesk-User.png)

### Standard Test User

* Username: TestUser

![Create Test User](Screenshots/09-Create-TestUser.png)

---

## Active Directory Administration

Verified all created users and groups within Active Directory Users and Computers.

![ADUC Overview](Screenshots/10-ADUC-Overview.png)

---

## Group Management

### ITAdmins Security Group

Added ITAdmin user to the ITAdmins group.

![ITAdmins Group Membership](Screenshots/11-ITAdmins-Group-Membership.png)

### HelpDesk Security Group

Added HelpDesk user to the HelpDesk security group.

![HelpDesk Group Membership](Screenshots/12-HelpDesk-Group-Membership.png)

---

## Skills Demonstrated

* Active Directory Administration
* Domain Controller Deployment
* User Account Management
* Security Group Administration
* Identity and Access Management (IAM)
* Windows Server Management
* Microsoft Enterprise Environment Fundamentals
* Documentation and Technical Reporting

---

## Results

Successfully deployed a Windows Server 2022 Active Directory environment, created user accounts, configured security groups, and verified group memberships using Active Directory administrative tools.

This project demonstrates foundational system administration skills commonly used in Help Desk, Desktop Support, and Junior Systems Administrator roles.

---

## Author

**Dante Walker**

Aspiring IT Support / Help Desk Professional

GitHub Portfolio Project
