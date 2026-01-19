# Windows Server 2025 Active Directory Home Lab

## Overview
Built a Windows Server 2025 Active Directory environment in Microsoft Azure to practice enterprise identity and access management.

## Environment
- Host OS: macOS
- Cloud Platform: Microsoft Azure
- Server OS: Windows Server 2025 (GUI)
- Server Role: Domain Controller
- Domain Name: lab.local
- Server Name: DC01

## Architecture
macOS (RDP Client)
→ Azure Virtual Machine
→ Windows Server 2025
→ Active Directory Domain Services + DNS

## Implementation Summary
- Deployed Windows Server 2025 VM in Azure
- Renamed server and configured networking
- Installed Active Directory Domain Services
- Promoted server to Domain Controller
- Created domain, users, and organizational units
- Verified authentication and domain membership
- Troubleshot domain administrator access

## Verification
- Confirmed domain membership via System Properties
- Validated authentication context using `whoami`
- Verified DNS forward lookup zones

## Skills Demonstrated
- Windows Server Administration
- Active Directory & DNS
- Azure Virtual Machines
- Identity and Access Management (IAM)
- Troubleshooting & Documentation

## Screenshots
Screenshots documenting each phase of the lab are included.
<img width="1470" height="956" alt="AD_Screenshot14" src="https://github.com/user-attachments/assets/511a0432-e8df-4239-b905-4cb3ff683931" />
<img width="1470" height="956" alt="AD_Screenshot13" src="https://github.com/user-attachments/assets/827b4eac-d619-4de3-abea-760f9dc9829a" />
<img width="1470" height="956" alt="AD_Screenshot12" src="https://github.com/user-attachments/assets/ec0c462c-ef3e-4421-8bfc-eb816f0508f7" />
<img width="1470" height="956" alt="AD_Screenshot11" src="https://github.com/user-attachments/assets/7439ad47-d27d-4a92-aca5-bd7bf6909987" />
<img width="1470" height="956" alt="AD_Screenshot10" src="https://github.com/user-attachments/assets/9bc4fa1b-b96c-4e67-8a3a-6b0dbb625dc1" />
<img width="1470" height="956" alt="AD_Screenshot9" src="https://github.com/user-attachments/assets/71e82d7f-187e-487e-9233-e6dd49e64076" />
<img width="1470" height="956" alt="AD_Screenshot8" src="https://github.com/user-attachments/assets/3c0b8e08-63a3-46ec-81f3-17081b814955" />
<img width="1470" height="956" alt="AD_Screenshot7" src="https://github.com/user-attachments/assets/c7815f69-1a4c-4810-8c44-de2d68e32b94" />
<img width="1470" height="956" alt="AD_Screenshot6" src="https://github.com/user-attachments/assets/4a9831c6-0eaa-4417-a0f6-d1ab07d2df92" />
<img width="1470" height="956" alt="AD_Screenshot5" src="https://github.com/user-attachments/assets/8dbfe5d5-055c-4a8b-8498-e0cbcce30660" />
<img width="1470" height="956" alt="AD_Screenshot4" src="https://github.com/user-attachments/assets/b48145e6-a6b5-4eea-bc83-e432aa923dcb" />
<img width="1470" height="956" alt="AD_Screenshot3" src="https://github.com/user-attachments/assets/377622b7-4469-4638-8a27-bff76df2cdf1" />
<img width="1470" height="956" alt="AD_Screenshot2" src="https://github.com/user-attachments/assets/28d1b468-d87c-4b5d-bc0a-25c904b2a79c" />
<img width="1470" height="956" alt="AD_Screenshot1" src="https://github.com/user-attachments/assets/de8dbbf7-c7b2-4cc8-b816-d1e98fa20fa1" />

