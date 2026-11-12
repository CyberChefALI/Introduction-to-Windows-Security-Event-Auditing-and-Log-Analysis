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


## STEP - 3  Hands-on Exercise:Event ID 4624: Successful Logon.

In this exercise, we will monitor, examine, and investigate successful logon attempts utilizing the Windows Event Viewer.


First, we will provision a new user account utilizing the Windows Command Prompt, subsequently execute an authentication attempt, and finally review and monitor the resulting event logs within the Windows Event Viewer.
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 14_11_11" src="https://github.com/user-attachments/assets/180d9e72-d004-4024-be8c-344476a319f2" />
<img width="1899" height="991" alt="Administrator_ Command Prompt 11_11_2026 14_18_40" src="https://github.com/user-attachments/assets/aa0b45f9-c21d-4cef-a686-af1221721667" />
<img width="1920" height="991" alt="Event Viewer 11_11_2026 14_19_42" src="https://github.com/user-attachments/assets/db7ac222-d4c8-4ecb-a5e3-988c1e6952b1" />


## STEP - 4  Hands-on Exercise:Event ID 4724: Password Reset

In this section, we will modify the password for the "cyberali" user account and subsequently monitor and analyze the resulting audit logs within the Windows Event Viewer.
<img width="1899" height="991" alt="Event Viewer 11_11_2026 14_26_04" src="https://github.com/user-attachments/assets/f38ac682-73e2-430e-af74-edb673f27114" />
<img width="1920" height="991" alt="Event Viewer 11_11_2026 14_26_36" src="https://github.com/user-attachments/assets/7a4267c4-e717-44c7-926f-c47abb229f8a" />

## STEP - 5  Hands-on Exercise:Event ID 102:  Security Log Cleared

In this exercise, we will attempt to clear all logs from the Windows Event Viewer and subsequently analyze how the system preserves a security audit record documenting the log-clearing event itself.
<img width="1920" height="991" alt="Event Viewer 11_11_2026 14_19_42" src="https://github.com/user-attachments/assets/9d5ab72a-be8c-427b-976f-d02227a056a6" />

<img width="1920" height="991" alt="Event Viewer 11_11_2026 14_29_23" src="https://github.com/user-attachments/assets/a1d00654-d1cf-4723-8951-6df7d4333a7a" />


## Conclusion:

* Comprehending Windows Security Logs is critical for detecting anomalous activity, including unauthorized authentication attempts, privilege escalation, and unauthorized modifications to system configurations.

* As a Security Operations Center (SOC) analyst, continuously examining and evaluating these logs is vital for identifying and addressing security incidents as they happen.

* Threat Detection: By tracking repeated failed logins, account lockouts, and privilege escalations, SOC analysts can rapidly identify malicious behavior across a network.


  ##  Created by CyberChefAli
