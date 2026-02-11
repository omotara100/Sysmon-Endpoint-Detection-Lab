# Netcat Connection Investigation

## MITRE ATT&CK
- T1049 – System Network Connections Discovery

## Activity
Netcat used to establish a raw TCP connection to the endpoint.

## Evidence
- Process creation event
- Network connection logged via Sysmon

## Analyst Notes
Netcat is frequently used for backdoors and command-and-control channels.

## Conclusion
Suspicious connection attempts successfully logged and analyzed.

