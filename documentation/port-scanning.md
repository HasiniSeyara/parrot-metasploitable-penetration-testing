
# 4.port-scanning

This documents how you used Nmap to discover open ports.

```markdown
# Port Scanning

## 1. Introduction
Port scanning is used to identify which network ports are open, closed or filtered on a target system.
Open ports may indicate services that are accessible through the network.
In this project, Nmap was used to investigate the Metasploitable 2 target.

## 2. Tool Used

Nmap (Network Mapper)

Nmap is a network discovery and security auditing tool.

## 3. TCP SYN Scan
The following command was used to investigate
TCP ports:

```bash
sudo nmap -sS -p- 192.168.62.128 -oN
evidence/scans/full-tcp-scan.txt
