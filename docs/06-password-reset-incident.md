# Password Reset Incident

## Incident INC0010008 – Password Reset

### Incident Summary

Emma Wilson contacted the IT Service Desk after forgetting her Windows password and was unable to sign in to her workstation. Following identity verification, the incident was logged in ServiceNow and assigned to the IT Support team.

The password was reset in Active Directory and the user successfully signed in using a new password.

---

## Investigation

### Purpose

Investigate the reported authentication issue and determine the appropriate action to restore the user's access.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Verified the user's identity.
- Confirmed that a password reset was required.

### Implementation Evidence

![Password Reset Incident Created](../Screenshots/12%20-%20Incident%20Password%20Reset%20Created.png)

![Password Reset Investigation](../Screenshots/13%20-%20Password%20Reset%20Investigation.png)

### Verification

The issue was confirmed to be a forgotten password requiring a password reset.

---

## Resolution

### Purpose

Reset the user's password and restore access to the domain.

### Procedure

- Opened Active Directory Users and Computers.
- Located the Emma Wilson account.
- Reset the password.
- Selected **User must change password at next logon**.
- Provided the temporary password to the user.
- Confirmed successful sign-in and password change.
- Updated the ServiceNow incident.
- Resolved and closed the ticket.

### Implementation Evidence

![Emma Wilson Password Reset](../Screenshots/14%20-%20Emma%20Wilson%20Password%20Reset.png)

![Password Successfully Changed](../Screenshots/15%20-%20Password%20Successfully%20Changed.png)

![Password Reset Incident Resolved](../Screenshots/16%20-%20Password%20Reset%20Incident%20Resolved.png)

### Verification

The user successfully signed in using the new password and confirmed access had been restored.

---

[← Previous: Account Lockout Incident](05-account-lockout-incident.md) | [Next: Shared Folder Access Incident →](07-shared-folder-access-incident.md)
