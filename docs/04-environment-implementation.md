# Environment Implementation

This section documents the implementation of the ServiceNow environment together with the dedicated IT Support technician workstation used throughout the project.

---

## Step 1 – Create the IT Support Technician Workstation (IT01)

### Purpose

The first stage of the project involved creating a dedicated Windows 11 Enterprise virtual machine to represent an IT Support technician's workstation. This workstation is used throughout the project to access ServiceNow, investigate incidents, administer Active Directory remotely and manage user support requests.

Creating a separate technician workstation provides a realistic enterprise support environment by separating the IT administrator's workstation from the employee's computer and the Domain Controller.

### Procedure

- Opened VMware Workstation Pro.
- Created a new virtual machine named IT01.
- Selected the Windows 11 Enterprise installation media.
- Configured the virtual machine hardware.
- Completed the Windows 11 installation.
- Confirmed the operating system booted successfully.

### Verification

The Windows 11 Enterprise virtual machine was successfully created and booted into the desktop without errors. The workstation was ready for further configuration.

### Implementation Evidence

![IT01 Windows 11 Desktop](../Screenshots/01%20-%20IT01%20Windows%2011%20Desktop.png)

---

## Step 2 – Configure the IT Support Workstation

### Purpose

Configure the IT Support workstation by installing essential software, applying system updates and preparing the environment for Active Directory administration and ServiceNow.

### Procedure

- Renamed the computer to IT01 where required.
- Installed VMware Tools.
- Installed Google Chrome.
- Checked for and installed Windows Updates.
- Verified internet connectivity.
- Confirmed the workstation was operating correctly.

### Verification

The IT Support workstation was successfully configured and ready for further software installation and administration tasks.

### Implementation Evidence

![Configured IT Support Workstation](../Screenshots/02%20-%20Configured%20IT%20Support%20Workstation.png)

---

## Step 3 – Join the IT Support Workstation to the Domain

### Purpose

Join the IT Support workstation (IT01) to the Active Directory domain, enabling administrators to authenticate using domain credentials and remotely manage the enterprise environment from a dedicated workstation.

### Procedure

- Verified network connectivity between IT01 and DC01.
- Opened the Windows system settings.
- Selected the option to join the Active Directory domain.
- Entered the domain name.
- Authenticated using domain administrator credentials.
- Restarted the workstation to apply the changes.

### Verification

IT01 successfully joined the Active Directory domain. Domain user authentication was verified after restart and the workstation became a member of the enterprise domain.

### Implementation Evidence

![IT01 Joined to Domain](../Screenshots/03%20-%20IT01%20Joined%20to%20Domain.png)

---

## Step 4 – Create a ServiceNow Developer Account

### Purpose

Create a ServiceNow Developer account to gain access to the ServiceNow Developer Program and obtain a Personal Developer Instance (PDI) for configuring and testing enterprise IT Service Management (ITSM) functionality.

### Procedure

- Navigated to the ServiceNow Developer Portal.
- Registered a new ServiceNow Developer account.
- Verified the account using the registered email address.
- Successfully signed in to the Developer Portal.

### Verification

The ServiceNow Developer account was successfully created and access to the Developer Portal was confirmed. The account was ready to request a Personal Developer Instance.

### Implementation Evidence

![ServiceNow Developer Portal](../Screenshots/04%20-%20ServiceNow%20Developer%20Portal.png)

---

## Step 5 – Request a Personal Developer Instance (PDI)

### Purpose

Request a Personal Developer Instance (PDI) to provide a dedicated ServiceNow environment for configuring and testing enterprise IT Service Management (ITSM) functionality.

The PDI serves as a sandbox where configurations and support scenarios can be developed without affecting production systems.

### Procedure

- Accessed the Request Instance option from the ServiceNow Developer Portal.
- Selected the desired ServiceNow release.
- Submitted the request for a new Personal Developer Instance.
- Waited for the instance to be provisioned automatically.
- Recorded the instance URL and administrator credentials.

### Verification

The Personal Developer Instance was successfully provisioned and was accessible using the administrator account provided by the ServiceNow Developer Program.

### Implementation Evidence

![Personal Developer Instance](../Screenshots/05%20-%20Personal%20Developer%20Instance.png)

---

## Step 6 – Access and Validate the ServiceNow Instance

### Purpose

Access the newly provisioned ServiceNow Personal Developer Instance (PDI) and verify that the platform is operational before beginning the enterprise IT support configuration.

### Procedure

- Opened the ServiceNow Personal Developer Instance using the instance URL.
- Signed in using the administrator account.
- Verified successful authentication.
- Confirmed the default ServiceNow homepage loaded successfully.
- Verified access to the Application Navigator and administrator interface.

### Verification

The ServiceNow Personal Developer Instance was successfully accessed and the administrator account was authenticated. The environment was confirmed to be operational and ready for configuration.

### Implementation Evidence

![ServiceNow Home Page](../Screenshots/06%20-%20ServiceNow%20Home%20Page.png)

---

## Step 7 – Familiarise with the ServiceNow Interface

### Purpose

Review the ServiceNow interface and identify the key modules used by IT Support technicians for incident management, user administration and service request fulfilment before beginning practical support activities.

### Procedure

- Signed in to the ServiceNow Personal Developer Instance.
- Explored the Application Navigator.
- Reviewed the Incident, Users and Knowledge modules.
- Verified access to the Service Desk interface.
- Confirmed the platform was ready for enterprise IT support activities.

### Verification

The ServiceNow environment was successfully accessed and the key modules required for the remainder of the project were available and functioning correctly.

### Implementation Evidence

![Company Configuration](../Screenshots/07%20-%20Company%20Configuration.png)

---

[← Previous: Solution Overview](03-solution-overview.md) | [Next: Account Lockout Incident →](05-account-lockout-incident.md)
