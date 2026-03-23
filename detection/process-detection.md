# Suspicious Process Execution Detection

## Description

Detected execution of a suspicious binary (svchost.exe) from a non-standard directory (C:\LabFiles).

## Query

```
SecurityEvent
| where EventID == 4688
| where NewProcessName contains "LabFiles"
```

## Analysis

The execution of svchost.exe outside the System32 directory indicates potential malicious activity. This behavior is commonly associated with malware attempting to masquerade as legitimate system processes.

## Evidence

(Insert screenshot here)
