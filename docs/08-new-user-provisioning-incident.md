# New User Provisioning Incident

## Incident INC0010012 – New User Account Creation

### Incident Summary

The Human Resources department contacted the IT Service Desk requesting the creation of a new Active Directory domain account for Daniel Carter, a new employee joining the Finance department.

The request was reviewed and the required user account was created, configured and assigned the appropriate departmental access before the incident was resolved.

---

## Investigation

### Purpose

Review the request for a new domain user account and confirm the information required to provision the account.

### Procedure

- Reviewed the incident submitted by Human Resources.
- Verified the employee's department and required account details.
- Confirmed the appropriate organisational unit and security group assignments.
- Prepared the account creation process.

### Implementation Evidence

![New User Incident Created](../Screenshots/23%20-%20New%20User%20Incident%20Created.png)

![New User Investigation](../Screenshots/24%20-%20New%20User%20Investigation.png)

### Verification

The information required to create the new domain account was verified before the account was provisioned.

---

## Resolution

### Purpose

Provision a new Active Directory domain account for the employee and assign the required departmental access.

### Procedure

- Created the new user account in Active Directory.
- Configured the user's initial password.
- Enabled **User must change password at next logon**.
- Added the user to the `Finance_Users` security group.
- Verified the account was successfully created within the Finance organisational unit.
- Confirmed the user could successfully sign in to the domain.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![User Account Configured](../Screenshots/24%20-%20User%20Account%20Configured.png)

![Active Directory User Created](../Screenshots/25%20-%20Active%20Directory%20User%20Created.png)

![Finance Security Group Assigned](../Screenshots/26%20-%20Finance%20Security%20Group%20Assigned.png)

![User Verified in Active Directory](../Screenshots/27%20-%20User%20Verified%20in%20Active%20Directory.png)

![Daniel Carter First Login](../Screenshots/28%20-%20Daniel%20Carter%20First%20Login.png)

![New User Incident Resolved](../Screenshots/29%20-%20New%20User%20Incident%20Resolved.png)

### Verification

The new Active Directory domain account was successfully provisioned, assigned the required Finance security group membership and verified through a successful first domain sign-in.

---

[← Previous: Shared Folder Access Incident](07-shared-folder-access-incident.md) | [Next: Software Installation Incident →](09-software-installation-incident.md)
