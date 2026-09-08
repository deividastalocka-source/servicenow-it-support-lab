# Shared Folder Access Incident

## Incident INC0010010 – Shared Folder Access

### Incident Summary

Sarah Jones from the HR department contacted the IT Service Desk after receiving an Access Denied message when attempting to access the HR shared folder.

The issue was investigated and identified as incorrect sharing permissions. The required permissions were restored, access to the shared folder was verified and the ServiceNow incident was resolved.

---

## Investigation

### Purpose

Investigate the user's shared folder access issue and determine why access to the HR departmental share was being denied.

### Procedure

- Reviewed the incident details in ServiceNow.
- Changed the incident state to In Progress.
- Confirmed that Sarah Jones was unable to access the HR shared folder.
- Tested access to the shared folder from the user's workstation.
- Verified that an Access Denied message was displayed.
- Reviewed the sharing permissions configured on the HR shared folder.
- Identified incorrect permissions as the cause of the access issue.

### Implementation Evidence

![Shared Folder Incident Created](../screenshots/17%20-%20Shared%20Folder%20Incident%20Created.png)

![Shared Folder Investigation](../screenshots/18%20-%20Shared%20Folder%20Investigation.png.png)

![HR Shared Folder Access Denied](../screenshots/19%20-%20HR%20Shared%20Folder%20Access%20Denied.png)

### Verification

Testing confirmed that Sarah Jones was unable to access the HR shared folder due to incorrect sharing permissions.

---

## Resolution

### Purpose

Restore the required permissions and verify that the user could successfully access the HR shared folder.

### Procedure

- Corrected the sharing permissions on the HR shared folder.
- Applied the updated permissions.
- Tested access from the user's workstation.
- Confirmed that Sarah Jones could successfully access the shared folder.
- Updated and resolved the ServiceNow incident.

### Implementation Evidence

![HR Share Permissions Restored](../screenshots/20%20-%20HR%20Share%20Permissions%20Restored.png)

![HR Shared Folder Access Restored](../screenshots/21%20-%20HR%20Shared%20Folder%20Access%20Restored.png)

![Shared Folder Incident Resolved](../screenshots/22%20-%20Shared%20Folder%20Incident%20Resolved.png)

### Verification

Sarah Jones successfully accessed the HR shared folder after the sharing permissions were corrected, confirming that access had been restored. The ServiceNow incident was then resolved.

---

[← Previous: Password Reset Incident](06-password-reset-incident.md) | [Next: New User Provisioning Incident →](08-new-user-provisioning-incident.md)
