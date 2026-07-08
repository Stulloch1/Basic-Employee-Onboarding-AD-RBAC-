# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group, a rapidly growing healthcare organization, relied on a third-party Managed Service Provider (MSP) to manage its identity lifecycle processes. While this approach met the company's initial needs, rapid expansion exposed significant weaknesses in its Identity and Access Management (IAM) program. User accounts and permissions were provisioned on an ad hoc basis without a formal Role-Based Access Control (RBAC) model, resulting in inconsistent access assignments and excessive privileges. Additionally, the organization lacked centralized audit trails and effective access governance, making it difficult to monitor user activity, demonstrate compliance, and satisfy HIPAA security requirements. These gaps increased the risk of unauthorized access, compliance violations, and operational inefficiencies, highlighting the need for a structured IAM solution with automated identity lifecycle management, RBAC, and comprehensive auditing.


## Solution Overview
* The solution was to build a basic employee onboarding pipeline in active directory. I set up the RBAC ,matrix and ensured users were given access ONLY according to their role. I also simulated a mock ticket where a user was provisioned the incorrect level of access. I was able to correct the issue and assigned the individual to their respectable department.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

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

