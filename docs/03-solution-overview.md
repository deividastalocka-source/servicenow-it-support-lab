# Solution Overview

## Enterprise Environment

The solution combines the Enterprise Active Directory Infrastructure Lab with a ServiceNow Personal Developer Instance to simulate a modern enterprise IT support environment.

ServiceNow acts as the central service desk platform while Windows Server provides the underlying infrastructure used to resolve support requests.

### Enterprise Lab Environment

![Enterprise Architecture Diagram](../Assets/Enterprise%20Architecture%20Diagram.png)

---

## Support Workflow

Support requests are raised within ServiceNow before being assigned to the appropriate technician. The issue is investigated using Windows Server administration tools before the resolution is recorded within ServiceNow and the ticket is formally closed.

---

## Project Workflow

The project follows a realistic enterprise support process consisting of:

1. User reports an issue.
2. Incident or service request created.
3. Ticket categorised and prioritised.
4. Investigation completed.
5. Resolution performed within Active Directory.
6. Resolution verified.
7. Ticket closed.
8. Knowledge article updated where appropriate.

---

[← Previous: Lab Environment](02-lab-environment.md) | [Next: Environment Implementation →](04-environment-implementation.md)
