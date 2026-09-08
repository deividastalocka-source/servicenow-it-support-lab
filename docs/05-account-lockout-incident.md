# Account Lockout Incident

## Incident INC0010006 – User Unable to Sign In

### Incident Summary

Michael Brown contacted the IT Service Desk after being unable to sign in to his Windows workstation. Following multiple unsuccessful password attempts, the user's Active Directory account became locked, preventing access to domain resources.

---

## Investigation

### Purpose

Determine the cause of the authentication failure and restore the user's access.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state from New to In Progress.
- Recorded initial work notes.
- Opened Active Directory Users and Computers from the IT01 workstation.
- Located Michael Brown's user account.
- Confirmed the account was locked following multiple failed sign-in attempts.

### Verification

The account lockout was confirmed as the cause of the authentication issue.

### Implementation Evidence

![Incident Created](../Screenshots/08%20-%20Incident%20Created.png)

![Michael Brown Account Locked](../Screenshots/09%20-%20Michael%20Brown%20Account%20Locked.png.png)

---

## Resolution

### Purpose

Restore user access and complete the incident.

### Procedure

- Unlocked the Active Directory account.
- Requested the user to attempt another sign-in.
- Verified successful authentication.
- Updated the incident with the resolution.
- Changed the incident state to Resolved.
- Closed the incident after user confirmation.

### Verification

Michael Brown successfully authenticated to the domain and confirmed that access to the Windows workstation had been restored.

### Implementation Evidence

![Michael Brown Account Unlocked](../Screenshots/10%20-%20Michael%20Brown%20Account%20Unlocked.png)

![Michael Brown Successful Sign-in](../Screenshots/11%20-%20Michael%20Brown%20Successful%20Sign-in.png)

![Incident Closed](../Screenshots/11%20-%20Incident%20Closed.png)

---

[← Previous: Environment Implementation](04-environment-implementation.md) | [Next: Password Reset Incident →](06-password-reset-incident.md)
