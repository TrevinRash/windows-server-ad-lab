# Windows Server 2025 Active Directory Home Lab
## Overview
Built a Windows Server 2025 Active Directory environment in Microsoft Azure to practice enterprise identity and access management.

## Phase 1: Server Preparation
- Deployed Windows Server 2025 VM in Azure
- Configured DNS loopback (127.0.0.1) and Azure-managed static private IP
- Verified system configuration
<img width="400" height="456" alt="Screenshot 2026-01-18 at 8 14 14 PM" src="https://github.com/user-attachments/assets/12f03d48-6fba-4a47-b93c-6d17fa6438c5" />
<img width="1470" height="956" alt="Screenshot 2026-01-18 at 8 17 25 PM" src="https://github.com/user-attachments/assets/0aa4262f-3843-4367-937d-e784623fe2fd" />

## Phase 2: Active Directory Deployment
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created new forest: lab.local
- Configured DNS during promotion
<img width="751" height="584" alt="AD_Screenshot1" src="https://github.com/user-attachments/assets/beff211f-18f4-48cc-a80a-2b0566c90ff4" />
<img width="955" height="507" alt="AD_Screenshot13" src="https://github.com/user-attachments/assets/56b32634-09a8-4cb0-b666-e0c30c9b6dd7" />

## Phase 3: Domain Verification
- Confirmed domain membership via System Properties
- Verified DNS forward lookup zone creation
- Validated authentication context using whoami

## Phase 4: Identity Management
- Created Organizational Units (OUs)
- Created domain users and security groups
- Verified domain authentication from non-admin account
