
# 3. reconnaissance
This explains how you approached the target from an attacker's perspective before attempting exploitation.

```markdown
# Reconnaissance

## 1. Introduction
Reconnaissance is the initial stage of a penetration test.
It involves collecting information about a target system before attempting to identify or exploit vulnerabilities.
In this project, Parrot Security OS was used to investigate the Metasploitable 2 machine.

## 2. Target Information

| Detail | Value |
|---|---|
| Target | Metasploitable 2 |
| Target IP | 192.168.62.128 |
| Attacker | Parrot Security OS |
| Attacker IP | 192.168.62.129 |
| Network | VMnet1 Host-only |

## 3. Tools Used
Nmap was used for network discovery and initial investigation of the target.

## 4. Host Discovery
he following command was used:

```bash
sudo nmap -sn 192.168.62.128
