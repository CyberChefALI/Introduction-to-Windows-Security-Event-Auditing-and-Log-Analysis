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

<img width="1000" height="998" alt="Screenshot 11_11_2026 13_43_12" src="https://github.com/user-attachments/assets/e13d9302-652a-4374-b289-ac9b0c382650" />
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_54_24" src="https://github.com/user-attachments/assets/cd7d5b03-157a-4396-874f-aa4be4f77dcd" />
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_55_37" src="https://github.com/user-attachments/assets/946c01b2-6d8d-4e85-b52b-ec231ab33f08" />


## STEP - 2  Hands-on Exercise: Event ID 4625 (Failed Logon Attempt)

In this exercise, we will monitor, examine, and investigate failed logon attempts utilizing the Windows Event Viewer.
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_59_15" src="https://github.com/user-attachments/assets/cf3fb68b-f79c-4521-837a-f12a3218cb3f" />
<img width="1920" height="991" alt="Administrator_ Command Prompt 11_11_2026 13_59_40" src="https://github.com/user-attachments/assets/99e7d701-562a-4e90-b174-b5a659beae09" />
<img width="1920" height="991" alt="Event Viewer 11_11_2026 13_59_52" src="https://github.com/user-attachments/assets/55406c04-fd29-4380-8ac7-992fe8c6f849" />
<img width="1920" height="991" alt="Event Viewer 11_11_2026 14_03_24" src="https://github.com/user-attachments/assets/876024b5-0452-4cc5-8b68-34c2485b0ccf" />
<img width="780" height="507" alt="Event Viewer 11_11_2026 14_04_10" src="https://github.com/user-attachments/assets/7ab7249e-a059-46ed-886a-b80492545420" />

