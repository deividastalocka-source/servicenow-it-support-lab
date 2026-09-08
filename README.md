# ServiceNow IT Support Lab

A hands-on IT support lab demonstrating enterprise-style incident management using ServiceNow, Microsoft Active Directory and Windows administration.

This project simulates a Service Desk environment where user issues are logged in ServiceNow, investigated on Windows systems, resolved using Active Directory and other administrative tools, verified with the user and documented before closure.

---

## Project Overview

The lab was designed to develop practical experience with common responsibilities performed by IT Support and Service Desk technicians.

Five end-to-end support scenarios were completed:

- Account lockout recovery
- Password reset
- Shared folder access troubleshooting
- New user account provisioning
- Software installation

Each scenario follows a structured support workflow from initial incident creation through investigation, technical resolution, verification and closure.

A ServiceNow knowledge article was also created to document a repeatable Active Directory user provisioning procedure.

---

## Enterprise Architecture

![Architecture Diagram](screenshots/Architecture%20Diagram.png)

The environment consists of:

- **ServiceNow Personal Developer Instance** – Incident management and knowledge management
- **DC01** – Windows Server 2025 domain controller running Active Directory Domain Services and DNS
- **IT01** – Windows 11 Enterprise workstation used by the IT support technician
- **PC01** – Windows 11 Enterprise client workstation representing the end user
- **VMware Workstation Pro** – Virtualisation platform hosting the Windows environment

---

## Support Workflow

The project follows a structured IT support process:

**User Issue → ServiceNow Incident → Investigation → Technical Resolution → Verification → Documentation → Closure**

ServiceNow acts as the central service management platform while Active Directory and Windows administration tools are used to resolve the underlying technical issues.

---

## IT Support Scenarios

| Incident | Scenario | Resolution |
|---|---|---|
| INC0010006 | User Unable to Sign In | Identified and unlocked a locked Active Directory account |
| INC0010008 | Password Reset | Reset the user's domain password and verified successful sign-in |
| INC0010010 | Shared Folder Access | Corrected sharing permissions and restored access |
| INC0010012 | New User Account Creation | Created and configured a new Finance domain user |
| INC0010013 | Software Installation | Installed and verified 7-Zip on the user's workstation |

---

## Technologies Used

- ServiceNow ITSM
- ServiceNow Incident Management
- ServiceNow Knowledge Management
- Windows Server 2025
- Windows 11 Enterprise
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy
- NTFS and shared folder permissions
- VMware Workstation Pro

---

## Documentation

Full implementation documentation is available below.

| Section | Documentation |
|---|---|
| 01 | [Project Overview](docs/01-project-overview.md) |
| 02 | [Lab Environment](docs/02-lab-environment.md) |
| 03 | [Solution Overview](docs/03-solution-overview.md) |
| 04 | [Environment Implementation](docs/04-environment-implementation.md) |
| 05 | [Account Lockout Incident](docs/05-account-lockout-incident.md) |
| 06 | [Password Reset Incident](docs/06-password-reset-incident.md) |
| 07 | [Shared Folder Access Incident](docs/07-shared-folder-access-incident.md) |
| 08 | [New User Provisioning Incident](docs/08-new-user-provisioning-incident.md) |
| 09 | [Software Installation Incident](docs/09-software-installation-incident.md) |
| 10 | [Knowledge Management](docs/10-knowledge-management.md) |
| 11 | [Conclusion and Lessons Learned](docs/11-conclusion-and-lessons-learned.md) |

---

## Repository Structure

```text
servicenow-it-support-lab/
│
├── docs/
│   ├── 01-project-overview.md
│   ├── 02-lab-environment.md
│   ├── 03-solution-overview.md
│   ├── 04-environment-implementation.md
│   ├── 05-account-lockout-incident.md
│   ├── 06-password-reset-incident.md
│   ├── 07-shared-folder-access-incident.md
│   ├── 08-new-user-provisioning-incident.md
│   ├── 09-software-installation-incident.md
│   ├── 10-knowledge-management.md
│   └── 11-conclusion-and-lessons-learned.md
│
├── screenshots/
│   ├── Architecture Diagram.png
│   └── Implementation evidence
│
├── LICENSE
└── README.md
```

---

## Skills Demonstrated

- ServiceNow incident management
- IT Service Management (ITSM)
- Active Directory administration
- User account provisioning
- Password resets and account lockout recovery
- Windows troubleshooting
- Shared folder and permission troubleshooting
- Software installation and verification
- Technical documentation
- Knowledge management
- Structured incident investigation and resolution

---

## Project Outcome

This project provided practical experience managing common IT support scenarios within a simulated enterprise environment.

It strengthened my ability to work through the complete support lifecycle: receiving and documenting user issues, investigating technical problems, administering Active Directory, implementing solutions, verifying successful resolution and maintaining clear technical documentation.

The project also demonstrated how ServiceNow can be integrated into a structured support process alongside Windows Server and Active Directory administration.
