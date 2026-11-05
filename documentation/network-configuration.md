# Network Configuration

## 1. Overview
The penetration-testing laboratory used a private virtual network to connect the attacker and target machines.
The network was configured using VMware Workstation Pro Host-only networking.

## 2. Network Topology
The laboratory contained two machines:
1. Parrot Security OS – Attacker.
2. Metasploitable 2 – Target.

### Network Diagram

```text
       VMware Workstation Pro
                |
          VMnet1 Host-only
                |
         192.168.62.0/24
                |
        -------------------
        |                 |
      Parrot           Metasploitable 2
      Attacker              Target
  192.168.62.129        192.168.62.128
