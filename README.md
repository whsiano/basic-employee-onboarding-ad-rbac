# Basic Employee Onboarding (AD)(RBAC)


## Problem Statement
* A fictional company called the Northstar Medical Group was mismanaged by a MSP (Managed Service Provider) in which they did not have a structured process of onboarding employees to the organization. New employees would have inconsistent access to resources and departments are disorganized in Active Directory. Since this company is in the healthcare sector, the mismanagement issue of their employees leads to HIPAA violations.

## Solution Overview
* I have rebuilt this company's employee onboarding process in Active Directory. I started off with creating a new domain called NMG.com. I then created OU's that represented each department with the proper employees added to them. I made sure to create the proper security groups that allow each employee the right access for their job duties. This implementation of RBAC (Role Based Access Control) improves security based on principle of least privilege, simplifies management when onboarding/off-boarding employees and satisfies HIPAA regulation.
  
## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* UTM
* RBAC (Role Based Access Control)

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards


