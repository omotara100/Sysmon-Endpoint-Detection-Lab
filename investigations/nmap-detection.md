# Nmap Network Scan Investigation

## MITRE ATT&CK
- T1046 – Network Service Scanning

## Activity
Nmap scan executed from Kali Linux against Windows endpoint.

## Evidence
- Sysmon Event ID 3
- Multiple inbound connections across many ports
- Repeated connection attempts from a single source IP

## Analyst Assessment
This activity matches reconnaissance behavior commonly seen before exploitation.

## Conclusion
Network scanning behavior successfully detected.
