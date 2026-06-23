# Splunk Enterprise Security Dashboard

## Overview
This is a Splunk dashboard that monitors successful and unsuccessful windows account logons. The search queries were configured with the filers '* source="WinEventLog:Security" EventCode=4624' for successful logons and '* source="WinEventLog:Security" EventCode=4625' for unsuccessful logons. The dashboard captures important windows security events of every successful and failed authentication on the local computer.
This dashboard monitors:

- Successful Account Logons
- Failed Account Logons

## Requirements
- Splunk Enterprise 
- Windows Event Logs
- Sysmon

## Dashboard Features
- Windows Account Logons
