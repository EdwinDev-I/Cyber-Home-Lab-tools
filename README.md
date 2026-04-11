# Cyber-Home-Security-Playbook

# For Incidence Response



## 1️⃣ Identify the Incident

First confirm that a breach is actually happening.

•	Check alerts from the Wazuh, Splunk, or other Security Information and Event Management (SIEM) tools.

•	Review logs for:

•	Suspicious logins

•	Unusual outbound traffic

•	Privilege escalation attempts

•	Data exfiltration activities

•	Determine:

•	Which systems are affected

•	How the attacker entered

•	What data is being stolen



## 2️⃣ Contain the Attack

Stop the attacker from spreading further.

•	Disconnect compromised systems from the network immediately.

•	Disable compromised accounts and credentials.

•	Block malicious IP addresses using a firewall or IDS like Suricata.

•	Apply network segmentation to isolate critical systems.

This prevents the attacker from continuing to steal data.



## 3️⃣ Eradicate the Threat

Remove the attacker and malicious artifacts.

•	Scan systems with antivirus and Endpoint Detection and Response (EDR) tools.

•	Remove malware, backdoors, or unauthorized software.

•	Patch vulnerabilities that the attacker exploited.

•	Reset all compromised passwords and keys.

•	Rebuild or reimage infected machines if necessary.



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

