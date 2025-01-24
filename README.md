# Azure SOC Lab

## Objective

Deployed a cloud-based Security Operations Center (SOC) lab using Microsoft Azure to monitor and analyze security events in real time. Configured a SIEM (Microsoft Sentinel) to ingest logs from a publicly exposed Windows VM, set up custom alert rules for suspicious RDP activity, and generated actionable security incidents. The project aimed to simulate real-world threat detection, incident response, and log analysis in a controlled environment at minimal cost.

### Skills Learned

- Azure Infrastructure Setup: Provisioning virtual machines (VMs), configuring resource groups, and managing public-facing services (RDP).
- SIEM Deployment: Configuring Microsoft Sentinel to aggregate and analyze logs from Azure resources.
- Threat Detection: Creating custom analytics rules in Sentinel to detect successful/failed RDP brute-force attempts.
- Incident Response: Triaging alerts and generating incidents for further investigation.
- Threat Intelligence: Understanding indicators of compromise (IoCs) and preparing for threat feed integration (mentioned as future work).

### Tools Used

- Microsoft Azure: Cloud platform for VM deployment and resource management.
- Azure Virtual Machine (Windows): Hosted a publicly accessible VM with RDP exposed.
- Microsoft Sentinel: SIEM for log ingestion, analytics, and incident management.

## Steps

**Azure VM Deployment**
![Screenshot_3](https://github.com/user-attachments/assets/8d40dfe9-2025-451f-a68e-475e94c4044c)
------------------------------------------
**Microsoft Sentinel Setup**
![Screenshot_4](https://github.com/user-attachments/assets/785401f6-ceed-4e97-916a-96a4880edd64)
------------------------------------------
**Data Connector Configuration**
![Screenshot_8](https://github.com/user-attachments/assets/83bc906c-89d7-4404-9a22-44e5ebcb5a8c)
------------------------------------------
**Custom Alert Rule Creation**
![Screenshot_10](https://github.com/user-attachments/assets/967e2d9c-098c-42af-bfba-36bfbb5df311)
------------------------------------------
