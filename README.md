#  Sysmon Endpoint Detection Lab

## Overview
This project demonstrates endpoint telemetry deployment, Windows event analysis,
endpoint investigation, and log-based detection engineering using Sysmon.

The lab simulates real attacker activity and shows how it is detected,
investigated, and converted into actionable detections aligned to MITRE ATT&CK.

## Objectives
- Deploy Sysmon with a hardened configuration
- Analyze Windows Security, System, and Sysmon logs
- Detect attacker behaviors such as network scanning and PowerShell abuse
- Build Sigma rules from observed telemetry

## Tools Used
- Sysmon (Sysinternals)
- Windows Event Viewer
- Kali Linux (Nmap, Netcat)
- PowerShell
- Sigma

## MITRE ATT&CK Techniques Covered
- T1046 – Network Service Scanning
- T1049 – System Network Connections Discovery
- T1059 – Command and Scripting Interpreter

## Project Structure
- `deployment/` – Sysmon installation and verification
- `windows-events/` – Windows and Sysmon event analysis
- `investigations/` – Endpoint attack investigations
- `detections/` – Sigma detection rules
- `mini_report.md` – Final analysis summary
