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
