# Introduction-to-Windows-Security-Event-Auditing-and-Log-Analysis

## OBJECTIVE - 

This lab teaches students how to navigate and examine Windows Security Logs to spot potential security threats. By exploring critical system events—such as user account modifications and login attempts—participants learn practical skills for identifying unauthorized activity and investigating security incidents.

## LAB SETUP -
System: Windows 10/11 or Windows Server 2019/2022

TOOLS:

Windows Event Viewer (pre-installed)

Administrative Privileges (to access certain security logs)

## What are Windows Security Logs?

Windows Security Logs contain records of security-related events on the system, such as

Successful login attempt

Failed login attempt

Password Reset

Security Logs Cleared

These logs are valuable for monitoring security incidents, detecting unauthorized access, and auditing system changes.


## Understanding Event IDs in Security Logs:

Some common Event IDs in Windows Security Logs that you will encounter include :

Event ID 4624: Successful Logon.

Event ID 4625: Failed Logon.

Event ID 4724: Password Reset

Event ID 102:  Security Log Cleared

## Practical Exercise: Investigation and Forensic Review of Windows Security Event Logs

For this hands-on exercise, we will examine and review the specified event logs.


## STEP - 1 Initialize Windows Command Shell 

OPEN Command prompt (Run as Administrator) & create user for the purpose of invistgation
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_55_37" src="https://github.com/user-attachments/assets/ca800192-4c41-4de8-85c8-3510f88ebdc7" />
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_54_24" src="https://github.com/user-attachments/assets/d3331513-6cae-4b92-9a79-2a0cfc0c2981" />
<img width="1000" height="998" alt="Screenshot 11_11_2026 13_43_12" src="https://github.com/user-attachments/assets/d0070747-0520-4cb5-8f27-e8ee530f1eb2" />



