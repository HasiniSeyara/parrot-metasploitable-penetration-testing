 Parrot OS vs Metasploitable 2
Controlled Penetration Testing Laboratory

Project Overview

This project documents a controlled penetration-testing practical conducted using Parrot Security OS against
Metasploitable 2 in an isolated VMware Host-only network.

The practical demonstrates network reconnaissance, port scanning, service enumeration, vulnerability research, controlled exploitation and network traffic analysis.

Lab Environment

| Component | Configuration |
|---|---|
| Attacker | Parrot Security OS |
| Target | Metasploitable 2 |
| Attacker IP | 192.168.62.129 |
| Target IP | 192.168.62.128 |
| Network | VMware VMnet1 Host-only |
| Subnet | 192.168.62.0/24 |

Tools

- Nmap
- Metasploit Framework
- SearchSploit
- tcpdump
- Wireshark
- Git

Learning Objectives

- Understand network reconnaissance.
- Identify open ports and running services.
- Investigate known vulnerabilities.
- Perform controlled exploitation in a training environment.
- Analyse network traffic.
- Understand evidence collection and security monitoring.

Project Structure

- documentation/ - Technical explanations.
- scripts/ - Supporting scripts.
- evidence/ - Sanitised practical evidence.
- reports/ - Final investigation report.

Scope and Ethics

All testing is restricted to the deliberately vulnerable
Metasploitable 2 virtual machine inside an isolated
VMware Host-only environment.

No external systems are authorised targets.

Project Status
completed 

Author
HasiniSeyara
