🏥 SOC Zero-Day Detection: Hospital Honeypot Scenario

🔎 Overview

This repository showcases a real-world style incident response walkthrough using SIEM data from a fictional hospital ("Northwell Grove Medical"). The scenario includes:

Zero-day exploitation

Honeypot deception detection

Sandbox isolation and threat analysis

Full NIST 800-53 + MITRE mapping

Remediation and policy alignment

Perfect for SOC analyst training, GRC interviews, or portfolio demonstration of detection logic and strategic response.

📊 Scenario Summary

A zero-day exploit was used to attempt access to an on-premise EHR system. SIEM alerts were triggered through a combination of:

Geolocation anomalies

Unusual process execution

Honeypot access

Through layered monitoring and deception tools, the attack was sandboxed, analyzed, and stopped before data exfiltration occurred.

⚡ Key Features

Raw alert timeline (SIEM log flow)

NIST 800-53 control mapping

MITRE ATT&CK techniques used

Custom remediation plan

Lessons learned

📃 Files Included

SIEM_Triage_ZeroDay_Hospital.md — Full incident timeline and analysis

Incident_Report_Hospital_ZeroDay.md — Executive-style security incident report

screenshot_siem_alerts.png — Simulated SIEM alert dashboard (honeypot triggered)

🔒 Compliance Reference

HIPAA (Electronic PHI protection)

NIST 800-53: IR-4, AU-6, SI-4, SC-7

MITRE Techniques: T1059, T1003, T1078, T1055

🚀 Use Cases

Security interview preparation

SOC analyst playbook building

GRC storytelling around technical risk

Created by Jasmine Alexander | TheDigitalGuardianFor learning, strategy, and sovereignty in cybersecurity

