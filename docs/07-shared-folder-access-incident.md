# Shared Folder Access Incident

## Incident INC0010010 – Shared Folder Access

### Incident Summary

Sarah Jones from the Human Resources department contacted the IT Service Desk after receiving an Access Denied message when attempting to access the HR network share.

The incident was logged in ServiceNow and investigated by the IT Support team. The issue was traced to incorrect sharing permissions on the network share. After restoring the required permissions, access was successfully verified and the incident was resolved.

---

## Investigation

### Purpose

Investigate the reported access issue and determine why the user was unable to access the HR network share.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Reviewed the HR shared folder configuration.
- Confirmed the reported Access Denied behaviour.
- Identified incorrect sharing permissions on the network share.

### Implementation Evidence

![Shared Folder Incident Created](../Screenshots/17%20-%20Shared%20Folder%20Incident%20Created.png)

![Shared Folder Investigation](../Screenshots/18%20-%20Shared%20Folder%20Investigation.png.png)

![HR Shared Folder Access Denied](../Screenshots/19%20-%20HR%20Shared%20Folder%20Access%20Denied.png)

### Verification

The issue was confirmed to be caused by incorrect sharing permissions on the HR network share.

---

## Resolution

### Purpose

Restore access to the HR network share by correcting the sharing permissions.

### Procedure

- Opened the HR folder properties.
- Reviewed the sharing configuration.
- Restored the required sharing permissions.
- Verified that the user could successfully access the shared folder.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![HR Share Permissions Restored](../Screenshots/20%20-%20HR%20Share%20Permissions%20Restored.png)

![HR Shared Folder Access Restored](../Screenshots/21%20-%20HR%20Shared%20Folder%20Access%20Restored.png)

![Shared Folder Incident Resolved](../Screenshots/22%20-%20Shared%20Folder%20Incident%20Resolved.png)

### Verification

The user successfully accessed the HR network share after the sharing permissions were restored.

---

[← Previous: Password Reset Incident](06-password-reset-incident.md) | [Next: New User Provisioning Incident →](08-new-user-provisioning-incident.md)
