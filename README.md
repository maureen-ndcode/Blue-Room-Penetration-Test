# Blue-Room-Penetration-Test
TryHackMe Blue Room penetration testing project
# Project Overview

This project documents a penetration test performed on the Blue Room machine from TryHackMe.
The objective was to identify vulnerabilities, gain initial access, escalate privileges, and retrieve user and system flags.
This project demonstrates practical skills in:
- Network scanning
- Vulnerability exploitation
- Password hash cracking
- Privilege escalation

# Objectives
- Identify open ports and running services
- Exploit vulnerabilities to gain access
- Dump and crack password hashes
- Escalate privileges to SYSTEM
- Retrieve user and root flags

# Tools Used
- Nmap
- Metasploit Framework
- Meterpreter
- John the Ripper
- Kali Linux

# Attack Flow
- Connected to the target network using VPN
- Scanned the target using Nmap
- Identified SMB vulnerability (MS17-010)
- Exploited EternalBlue using Metasploit
- Obtained a Meterpreter session
- Dumped password hashes
- Cracked hashes using John the Ripper
- Escalated privileges
- Retrieved flags

# Key Skills Demonstrated
- Network reconnaissance
- Exploiting SMB vulnerabilities
- Password cracking
- Post-exploitation techniques
- Privilege escalation

# Mitigation / Defense Recommendations
- To prevent similar attacks:
- Apply security patches (MS17-010)
- Disable SMBv1
- Use strong password policies
- Monitor suspicious network activity
- Implement endpoint security tools

# Learning Outcomes
Through this project, I learned:
- How to perform structured penetration testing
- How EternalBlue exploitation works
- How to handle Meterpreter sessions
- How password hash cracking is performed in real scenarios

# Project Report
The full step-by-step report with screenshots is available here:
[Full Report](The_Blue_Room_Penetration_Test_Report.pdf)


# Author
Maureen
Cybersecurity Student | Ethical Hacking Enthusiast
