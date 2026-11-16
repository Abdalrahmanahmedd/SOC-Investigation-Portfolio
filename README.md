# SOC Analyst Practical Investigation Portfolio

**Copyright © 2026 Abdelrahman Ahmed. All Rights Reserved.**

All original investigation documentation, written analysis, explanations, and portfolio materials in this repository are my intellectual work unless otherwise stated.

Unauthorized reproduction, redistribution, or commercial use of my original materials without prior written permission is prohibited.

---

## About This Portfolio

This repository documents my hands-on cybersecurity investigations and practical exercises focused on Security Operations Center (SOC) operations and Blue Team activities.

The objective is to demonstrate practical investigation skills, security event analysis, threat identification, evidence correlation, and incident response methodologies.

Rather than simply documenting alert findings, each investigation focuses on the analytical process, investigation decisions, supporting evidence, and conclusions.

## Investigation Index

| # | Investigation | Platform | Status |
|---|---|---|---|
| 01 | Phishing Email Investigation | Let'sDefend | Completed |
| 02 | External Network Scanning Investigation | TBD | Planned |
| 03 | Brute Force Attack Investigation | TBD | Planned |
| 04 | Suspicious PowerShell Execution | TBD | Planned |
| 05 | Malware Execution Investigation | TBD | Planned |

### Case 01 – Phishing Email Investigation

**Scenario:** Investigation of a phishing email that resulted in malicious file execution on the recipient's endpoint.

**Key investigation areas:**
- Email Gateway Investigation
- Proxy Log Analysis
- URL and File Analysis
- Threat Intelligence using VirusTotal
- EDR Investigation
- Process Tree Analysis
- IOC Identification and Consolidation
- Incident Containment

**Tools and platforms:** Let'sDefend, VirusTotal, Email Gateway, Proxy Logs, EDR.

[View Investigation](01-Phishing-Email-Investigation.pdf)

---

## Investigation Methodology

My investigations follow a structured SOC workflow:

1. **Alert Triage:** Review alert details, severity, and detection context.
2. **Alert Assignment:** Establish investigation ownership.
3. **Initial Assessment:** Understand the triggered detection and available event information.
4. **Evidence Collection:** Gather relevant logs and telemetry from security tools.
5. **Investigation and Correlation:** Analyze evidence across different security layers.
6. **Threat Identification:** Identify IOCs and assess suspicious activity.
7. **Incident Classification:** Determine whether the alert is a True Positive, False Positive, or requires further investigation.
8. **Incident Response:** Recommend or perform appropriate containment and remediation actions.

## Skills Demonstrated

- Security Alert Triage
- Phishing Investigation
- Email Security Analysis
- Network Log Analysis
- Threat Intelligence
- IOC Analysis
- Windows Process Analysis
- Endpoint Detection and Response (EDR)
- MITRE ATT&CK Mapping
- Incident Response

## Tools & Technologies

- Let'sDefend
- VirusTotal
- SIEM / Log Management
- Email Security Gateways
- Proxy Logs
- Endpoint Detection and Response (EDR)
- MITRE ATT&CK Framework

## Disclaimer

These investigations are conducted in simulated or authorized lab environments for educational and professional development purposes.

Third-party platform screenshots, tools, and materials remain the property of their respective owners.

No unauthorized systems or networks are targeted. Malicious indicators are documented for defensive security purposes.

## About the Author

**Abdelrahman Ahmed**

Computer Engineering graduate specializing in Cybersecurity, with practical SOC exposure through CIB and NTI training.

Currently developing hands-on skills in SOC operations, threat detection, security monitoring, incident investigation, and response.

**GitHub:** [Abdalrahmanahmedd](https://github.com/Abdalrahmanahmedd)

---

*Continuously learning. Continuously investigating. Building practical Blue Team skills.*
