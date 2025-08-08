# Task 4 – Setup and Use a Firewall (Windows)

## Objective
Configure and test basic firewall rules to allow or block traffic using Windows Defender Firewall with Advanced Security.

---

## Tool Used
- **Windows Defender Firewall with Advanced Security**
- OS: Windows 10/11

---

## Steps Performed
1. Opened Windows Defender Firewall with Advanced Security using `wf.msc`.
2. Navigated to **Inbound Rules** to create a new firewall rule.
3. Named the rule **task4** for tracking purposes.
4. Configured the rule to **Allow the connection if it is secure**.
5. Selected **Protocol: TCP**, applied to **All Local Ports**, and set **Remote Port: 118**.
6. Saved and enabled the rule.
7. Verified that the rule was successfully added to the firewall rules list.

---

## Rule Details
- **Name:** task4  
- **Action:** Allow the connection if it is secure  
- **Protocol:** TCP  
- **Local Port:** All Ports  
- **Remote Port:** 118  
- **Profile:** All  
- **Enabled:** Yes  

---

## Screenshots
![Firewall Rule List](screenshots/windows_inbound_rules.png)  
![Firewall Rule General Tab](screenshots/firewall_general.png)  
![Firewall Rule Protocol Tab](screenshots/firewall_protocols.png)  

---

## Summary
The firewall rule **task4** was successfully created to allow secure TCP connections on remote port 118 from any local port.  
This configuration demonstrates how Windows Firewall can be used to:
- Control network access based on port and protocol.
- Enforce secure connections.
- Reduce the attack surface by restricting unauthorized connections.

---

## Key Learnings
- Inbound rules manage incoming traffic to your device.
- Using specific ports and protocols helps fine-tune security.
- Windows Firewall’s GUI (`wf.msc`) provides an easy way to configure advanced network filtering rules.
