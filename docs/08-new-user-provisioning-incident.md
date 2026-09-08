# New User Provisioning Incident

## Incident INC0010012 – New User Account Creation

### Incident Summary

A request was submitted to the IT Service Desk to create a new Active Directory account for Daniel Carter, a new employee joining the Finance department.

The request was investigated, a new domain user account was created in the Finance organisational unit, the user was assigned to the Finance_Users security group and successful access was verified before the ServiceNow incident was resolved.

---

## Investigation

### Purpose

Review the new user request and confirm the account requirements before provisioning the user within Active Directory.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Confirmed the new user's details and departmental requirements.
- Identified the Finance organisational unit as the appropriate location for the account.
- Identified the Finance_Users security group required for departmental access.

### Implementation Evidence

![New User Incident Created](../screenshots/23%20-%20New%20User%20Incident%20Created.png)

![New User Investigation](../screenshots/24%20-%20New%20User%20Investigation.png)

### Verification

The investigation confirmed the information required to provision Daniel Carter with a Finance domain account and the appropriate departmental access.

---

## Resolution

### Purpose

Create and configure the new Active Directory user account, assign the required group membership and verify successful domain access.

### Procedure

- Created a new Active Directory user account for Daniel Carter.
- Placed the account within the Finance organisational unit.
- Configured the required user account settings.
- Added Daniel Carter to the Finance_Users security group.
- Verified the account within Active Directory.
- Performed the user's first domain sign-in.
- Confirmed that the account was functioning correctly.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![User Account Configured](../screenshots/24%20-%20User%20Account%20Configured.png)

![Active Directory User Created](../screenshots/25%20-%20Active%20Directory%20User%20Created.png)

![Finance Security Group Assigned](../screenshots/26%20-%20Finance%20Security%20Group%20Assigned.png)

![User Verified in Active Directory](../screenshots/27%20-%20User%20Verified%20in%20Active%20Directory.png)

![Daniel Carter First Login](../screenshots/28%20-%20Daniel%20Carter%20First%20Login.png)

![New User Incident Resolved](../screenshots/29%20-%20New%20User%20Incident%20Resolved.png)

### Verification

Daniel Carter successfully signed in using the newly created domain account, confirming that the account had been provisioned correctly and was ready for use. The ServiceNow incident was then resolved.

---

[← Previous: Shared Folder Access Incident](07-shared-folder-access-incident.md) | [Next: Software Installation Incident →](09-software-installation-incident.md)
