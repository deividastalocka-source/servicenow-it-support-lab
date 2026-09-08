# Password Reset Incident

## Incident INC0010008 – Password Reset

### Incident Summary

Emma Wilson contacted the IT Service Desk after being unable to access her domain account because she had forgotten her password.

The request was investigated, the user's password was reset in Active Directory and the user was required to change the temporary password at the next sign-in. Successful access was verified before the ServiceNow incident was resolved.

---

## Investigation

### Purpose

Investigate the user's authentication issue and determine the appropriate action required to restore access to the domain account.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Confirmed that Emma Wilson required a password reset.
- Accessed Active Directory Users and Computers.
- Located Emma Wilson's domain account.

### Implementation Evidence

![Password Reset Incident Created](../screenshots/12%20-%20Incident%20Password%20Reset%20Created.png)

![Password Reset Investigation](../screenshots/13%20-%20Password%20Reset%20Investigation.png)

### Verification

The investigation confirmed that a password reset was required to restore access to Emma Wilson's domain account.

---

## Resolution

### Purpose

Reset the user's domain password and verify that the user could successfully regain access to the account.

### Procedure

- Reset Emma Wilson's password in Active Directory.
- Configured the account to require a password change at the next sign-in.
- Provided the temporary password for the initial sign-in.
- Signed in using the temporary credentials.
- Changed the password when prompted.
- Verified successful access to the domain account.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![Emma Wilson Password Reset](../screenshots/14%20-%20Emma%20Wilson%20Password%20Reset.png)

![Password Successfully Changed](../screenshots/15%20-%20Password%20Successfully%20Changed.png)

![Password Reset Incident Resolved](../screenshots/16%20-%20Password%20Reset%20Incident%20Resolved.png)

### Verification

Emma Wilson successfully changed the temporary password and regained access to the domain account. The ServiceNow incident was then resolved.

---

[← Previous: Account Lockout Incident](05-account-lockout-incident.md) | [Next: Shared Folder Access Incident →](07-shared-folder-access-incident.md)
