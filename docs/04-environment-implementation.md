# Environment Implementation

## IT Support Workstation

### Purpose

Create a dedicated Windows 11 Enterprise workstation for the IT support technician to manage ServiceNow incidents and perform administrative support tasks.

### Procedure

- Created a new Windows 11 Enterprise virtual machine in VMware Workstation Pro.
- Configured the workstation as IT01.
- Installed VMware Tools.
- Verified that the workstation was operational.

### Implementation Evidence

![IT01 Windows 11 Desktop](./screenshots/01%20-%20IT01%20Windows%2011%20Desktop.png)

![Configured IT Support Workstation](../screenshots/02%20-%20Configured%20IT%20Support%20Workstation.png)

### Verification

IT01 was successfully configured as the dedicated IT support workstation.

---

## Domain Configuration

### Purpose

Join the IT support workstation to the existing Active Directory domain to provide access to domain resources and administrative tools.

### Procedure

- Configured the network settings on IT01.
- Connected the workstation to the existing Windows Server 2025 domain environment.
- Joined IT01 to the Active Directory domain.
- Restarted the workstation to complete the domain join.

### Implementation Evidence

![IT01 Joined to Domain](../screenshots/03%20-%20IT01%20Joined%20to%20Domain.png)

### Verification

IT01 successfully joined the domain and was available for use as the technician workstation.

---

## ServiceNow Developer Environment

### Purpose

Configure a ServiceNow Personal Developer Instance to provide the service management platform used throughout the project.

### Procedure

- Accessed the ServiceNow Developer Portal.
- Provisioned a Personal Developer Instance.
- Opened the ServiceNow environment.
- Verified access to the ServiceNow platform.

### Implementation Evidence

![ServiceNow Developer Portal](../screenshots/04%20-%20ServiceNow%20Developer%20Portal.png)

![Personal Developer Instance](../screenshots/05%20-%20Personal%20Developer%20Instance.png)

![ServiceNow Home Page](../screenshots/06%20-%20ServiceNow%20Home%20Page.png)

### Verification

The ServiceNow Personal Developer Instance was successfully provisioned and accessible from the IT support workstation.

---

## Company Configuration

### Purpose

Configure the ServiceNow environment to represent the organisation used throughout the IT support scenarios.

### Procedure

- Accessed the company configuration settings within ServiceNow.
- Configured the organisation information used throughout the project.
- Verified that the configuration was successfully applied.

### Implementation Evidence

![Company Configuration](../screenshots/07%20-%20Company%20Configuration.png)

### Verification

The company configuration was successfully applied within the ServiceNow environment and was ready for the IT support scenarios.

---

[← Previous: Solution Overview](03-solution-overview.md) | [Next: Account Lockout Incident →](05-account-lockout-incident.md)
