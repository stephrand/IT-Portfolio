# Active Directory Homelab

## Project Overview

This project documents the creation of a Windows Server 2016 Active Directory environment based on the fictional company Dunder Mifflin from The Office.

The lab was built to gain hands-on experience with Active Directory administration, DNS, Group Policy, file services, PowerShell automation, and Windows enterprise infrastructure.

---

## Environment

| Component         | Details             |
| ----------------- | ------------------- |
| Domain Controller | Windows Server 2016 |
| Client            | Windows 10          |
| Domain            | dundermifflin.local |
| Hostname          | DC01                |

---

## Core Infrastructure

### Active Directory & DNS

Documentation covering domain deployment, OU structure, users, groups, and DNS configuration.

➡️ [View Active Directory Documentation](active-directory.md)

![Domain Controller](screenshots/domain-controller.png)

---

### Security Hardening

Documentation covering least privilege implementation, user restrictions, workstation security baselines, and administrative controls.

➡️ [View Security Documentation](security-hardening.md)

![Security Baseline](screenshots/block-ctrl-panel.png)

---

### Group Policy

Documentation covering Group Policy Objects, drive mapping, and policy deployment.

➡️ [View Group Policy Documentation](group-policy.md)

---

### File Services

Documentation covering home folders, roaming profiles, and PowerShell automation.

➡️ [View File Services Documentation](file-shares.md)

---

## Project Status

| Component                   | Status   |
| --------------------------- | -------- |
| Active Directory Deployment | Complete |
| DNS Configuration           | Complete |
| User & Group Administration | Complete |
| Group Policy Drive Mapping  | Complete |
| Home Directories            | Complete |
| Roaming Profiles            | Complete |
| Departmental File Shares    | Complete |
| Least Privilege             | Complete |
| Security Baseline           | Complete |
| Software Deployment         | Planned |

---

## Validation

Windows 10 client successfully joined to the domain and receiving Group Policy settings.

![Domain Join and Home Drive](screenshots/mapped-home-drive-domain-join.png)

---

## Skills Demonstrated

* Active Directory Administration
* DNS Configuration
* Group Policy Management
* Windows Server Administration
* PowerShell Automation
* User Provisioning
* File Share Permissions
* NTFS Permissions
* Security Group Management
* Least Privilege Administration
* Windows Defender Management
* Windows Firewall Configuration
* Security Baseline Deployment
* Domain Authentication

---

## Future Improvements

* Software Deployment via GPO
* Password Policies
* Account Lockout Policies
* AppLocker Implementation
* DHCP Services
* Remote Desktop Administration
* Additional Domain Clients
* WSUS Integration
* Tiered Administrative Accounts
