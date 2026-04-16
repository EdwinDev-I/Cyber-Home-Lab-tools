# Incident Response Playbook 📚

# Wazuh SOC Detection Lab (AWS Windows Server)



## Overview

This repository contains an Incident Response Playbook developed for a Security Operations Center (SOC) detection lab built using Wazuh on Amazon Web Services.

The purpose of this playbook is to document the standard procedures for detecting, investigating, containing, and responding to security incidents generated within the lab environment.

The lab monitors a Windows Server endpoint with a Wazuh Agent, while simulated attacks are launched from Kali Linux.

This playbook focuses on detecting and responding to:

	•	Brute-force authentication attempts
  
	•	Network reconnaissance scanning
	
  •	Suspicious authentication activity
	
  •	Unauthorized access attempts

The detection rules and alerts generated align with techniques from the MITRE ATT&CK.



## 1️⃣ Lab Architecture

**Infrastructure**

Component       Description

AWS Cloud       Hosts the Windows Server envirinment

Wazuh Manager   Centralized log monitoring and analysis

Wazuh Agent     Installed on Windows Server

Kali Linux      Used to simulate attacker activity

**Data Flow**

	1.	Windows Server generates system and security logs.
  
	2.	The Wazuh Agent collects the logs.
	
  3.	Logs are forwarded to the Wazuh Manager.
	
  4.	Wazuh rules analyze logs and generate alerts.
	
  5.	Alerts appear in the Wazuh dashboard for SOC investigation.



## 2️⃣ Incident Response Lifecycle

The incident response workflow follows the standard SOC methodology.

1️⃣ Preparation

2️⃣ Detection and Analysis

3️⃣ Containment

4️⃣ Eradication

5️⃣ Recovery

6️⃣ Lessons Learned



## 4️⃣ Recover Systems

Bring the system back to normal operations.

•	Restore affected systems from clean backups.

•	Monitor network traffic to ensure the attacker is gone.

•	Reconnect systems to the network gradually.

•	Verify system integrity.



## 5️⃣ Post-Incident Analysis

Understand how the attack happened and prevent it in the future.

•	Conduct digital forensics to analyze the attack path.

•	Document the timeline of the breach.

•	Update security policies and procedures.

•	Train staff on phishing and security awareness.


## 6️⃣ Strengthen Security Controls

Implement stronger defenses to prevent future attacks:

•	Deploy Multi-Factor Authentication (MFA).

•	Implement a Zero Trust security model.

•	Improve log monitoring with SIEM tools.

•	Conduct regular penetration testing and vulnerability scans.





## Get the full Wazuh, and Suricata setup in my code section and troubleshooting guides also if necessary 

