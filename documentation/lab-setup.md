## Lab Setup – Parrot OS vs Metasploitable 2

## 1. Introduction
This project uses a controlled virtual penetration-testing environment to understand how attackers identify vulnerabilities and exploit weaknesses in computer systems.
The laboratory consists of two virtual machines:
- Parrot Security OS – Attacker machine.
- Metasploitable 2 – Deliberately vulnerable target machine.
The environment was created using VMware Workstation Pro.

## 2. Objectives
The objectives of setting up this laboratory were:
- To create an isolated penetration-testing environment.
- To understand attacker and target machine configurations.
- To practise network reconnaissance.
- To identify vulnerable services.
- To research known vulnerabilities.
- To perform controlled exploitation.
- To observe the results of a successful exploitation attempt.

## 3. Software and Tools

| Software | Purpose |
|---|---|
| VMware Workstation Pro | Virtual machine management |
| Parrot Security OS | Attacker operating system |
| Metasploitable 2 | Vulnerable target machine |
| Nmap | Network discovery and scanning |
| Metasploit Framework | Vulnerability exploitation |
| SearchSploit | Vulnerability research |
| tcpdump | Network packet capture |
| Git | Version control |
| GitHub | Project hosting and documentation |

## 4. Virtual Network Configuration
Both virtual machines were configured to use VMware VMnet1 (Host-only networking).
This configuration allowed communication between the two virtual machines without intentionally exposing the vulnerable target to an external network.

 Network Details

| Configuration | Value |
|---|---|
| Network type | Host-only |
| Virtual network | VMnet1 |
| Subnet | 192.168.62.0/24 |
| Attacker IP | 192.168.62.129 |
| Target IP | 192.168.62.128 |

## 5. Laboratory Safety
All penetration-testing activities were conducted against the deliberately vulnerable Metasploitable 2 virtual machine.
The target was kept within the isolated laboratory network.
No unauthorised external systems were included in the testing scope.

## 6. Outcome
The laboratory was successfully configured, allowing the Parrot machine to communicate with the Metasploitable target.
This provided the foundation for the reconnaissance, vulnerability assessment and exploitation stages.
