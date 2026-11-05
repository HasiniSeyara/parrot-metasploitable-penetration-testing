
## Network-analysis

This documents packet capture and the defensive value of observing attacker traffic.

```markdown
# Network Traffic Analysis

## 1. Introduction
Network traffic analysis involves examining communication between systems to understand
network activity and identify potentially suspicious
behaviour.

In this project, tcpdump was explored as a tool for capturing network packets during penetration
testing activities.

## 2. Tool Used

tcpdump

tcpdump is a command-line packet analyser that allows users to capture and inspect network traffic.

## 3. Identifying the Network Interface
Before capturing traffic, the network interface used to reach the target must be identified.

Example:

```bash
ip route get 192.168.62.128
