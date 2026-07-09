# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group, a rapidly growing healthcare organization, relied on a third-party Managed Service Provider (MSP) to manage its identity lifecycle processes. While this approach met the company's initial needs, rapid expansion exposed significant weaknesses in its Identity and Access Management (IAM) program. User accounts and permissions were provisioned on an ad hoc basis without a formal Role-Based Access Control (RBAC) model, resulting in inconsistent access assignments and excessive privileges. Additionally, the organization lacked centralized audit trails and effective access governance, making it difficult to monitor user activity, demonstrate compliance, and satisfy HIPAA security requirements. These gaps increased the risk of unauthorized access, compliance violations, and operational inefficiencies, highlighting the need for a structured IAM solution with automated identity lifecycle management, RBAC, and comprehensive auditing.


## Solution Overview
* To solve these issues, I built a basic employee onboarding process in Active Directory and created a Role-Based Access Control (RBAC) matrix to ensure employees received the correct access based on their job roles. Instead of assigning permissions manually, users were placed into the appropriate security groups to provide consistent and secure access. I also simulated a help desk ticket where an employee was accidentally given the wrong level of access. After reviewing the request, I removed the unnecessary permissions and assigned the user to the correct department and security groups, demonstrating proper user provisioning, access management, and the principle of least privilege.


## Video Walkthrough
* https://www.loom.com/share/d41a7ab5671b4e8f9093028e98b25095

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Solved a mock ticket where a user was given the incorrect access
* I fully documented my steps end-to-end.

