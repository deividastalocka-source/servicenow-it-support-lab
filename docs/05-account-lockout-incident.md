# Account Lockout Incident

## Incident INC0010006 – User Unable to Sign In

### Incident Summary

Michael Brown from the Finance department contacted the IT Service Desk after being unable to sign in to his domain account.

Investigation identified that the account had been locked in Active Directory. The account was unlocked, user access was verified and the ServiceNow incident was resolved.

---

## Investigation

### Purpose

Investigate the user's sign-in issue and identify the cause of the authentication failure.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Accessed Active Directory Users and Computers.
- Located Michael Brown's domain account.
- Confirmed that the account was locked.

### Implementation Evidence

![Incident Created](../screenshots/08%20%E2%80%93%20Incident%20Created.png)

![Michael Brown Account Locked](../screenshots/09%20-%20Michael%20Brown%20Account%20Locked.png.png)

### Verification

Active Directory confirmed that Michael Brown's account was locked, preventing the user from successfully authenticating to the domain.

---

## Resolution

### Purpose

Restore access to the user's domain account and verify that authentication was functioning correctly.

### Procedure

- Unlocked Michael Brown's account in Active Directory.
- Applied the account changes.
- Verified that the account was no longer locked.
- Tested the user's domain sign-in.
- Confirmed that Michael Brown could successfully access the workstation.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![Michael Brown Account Unlocked](../screenshots/10%20-%20Michael%20Brown%20Account%20Unlocked.png)

![Michael Brown Successful Sign-in](../screenshots/11%20-%20Michael%20Brown%20Successful%20Sign-in.png)

![Incident Closed](../screenshots/11%20-%20Incident%20Closed.png)

### Verification

Michael Brown successfully signed in using his domain account, confirming that access had been restored. The ServiceNow incident was then closed.

---

[← Previous: Environment Implementation](04-environment-implementation.md) | [Next: Password Reset Incident →](06-password-reset-incident.md)
