# PowerShell Outbound Network Investigation

## MITRE ATT&CK
- T1059 – Command and Scripting Interpreter

## Activity
PowerShell executed with outbound web request.

## Evidence
- Sysmon Event ID 3
- Process Image: powershell.exe
- External network connection observed

## Detection Value
PowerShell outbound traffic is a high-confidence indicator of malicious activity.

## Conclusion
PowerShell network activity successfully detected and logged.

