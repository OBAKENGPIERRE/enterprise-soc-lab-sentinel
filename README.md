# Enterprise SOC Lab – Attack Simulation & Detection

## Overview

This project simulates a full cyber attack lifecycle and demonstrates detection using Microsoft Sentinel.

## Objectives

* Simulate real-world attack techniques
* Implement persistence and data exfiltration
* Detect malicious activity using SIEM
* Analyze endpoint protection behavior

## Lab Environment

* Kali Linux (Attacker)
* Windows 10 (Victim)
* Sysmon (Telemetry)
* Microsoft Sentinel (SIEM)

## Attack Phases

* Initial Access (USB / Phishing simulation)
* Execution (Malicious payload)
* Command & Control (Reverse shell)
* Persistence (Registry / Scheduled Task)
* Data Exfiltration

## Detection Capabilities

* Process execution monitoring
* Network anomaly detection
* Persistence detection
* Defender alerts
* File access monitoring

## Key Findings

* Endpoint protection (Defender) blocked persistence
* Payload execution detectable via Sysmon and Security logs
* C2 traffic identifiable through network telemetry
* SIEM detection depends on proper log ingestion

## MITRE ATT&CK Mapping

* T1204 – User Execution
* T1071 – Command and Control
* T1547 – Persistence
* T1041 – Exfiltration

## Conclusion

This lab demonstrates both offensive and defensive perspectives, highlighting how modern defenses disrupt attacks and how SIEM tools can detect malicious activity.
