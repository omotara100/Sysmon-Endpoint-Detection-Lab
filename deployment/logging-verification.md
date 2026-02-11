# Sysmon Logging Verification

## Objective
Verify that Sysmon is actively logging endpoint activity.

## Verification Steps
1. Open Event Viewer
2. Navigate to:
   Applications and Services Logs  
   → Microsoft  
   → Windows  
   → Sysmon  
   → Operational

## Event IDs Observed
- Event ID 1 – Process Creation
- Event ID 3 – Network Connection
- Event ID 10 – Process Access
- Event ID 11 – File Creation

## Conclusion
Sysmon logging confirmed and operational.

