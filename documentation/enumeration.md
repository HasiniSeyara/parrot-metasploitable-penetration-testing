
# 5. Enumeration

This is where you explain what you discovered about the services running on Metasploitable 2.

```markdown
# Service Enumeration

## 1. Introduction

Service enumeration involves collecting detailed
information about services running on a target system.

After identifying open ports, the next step is to
investigate the applications and versions associated
with those ports.

## 2. Identified Services

During the investigation, the following services
were identified on the target:

| Port | Service | Identified Version |
|---|---|---|
| 21 | FTP | vsftpd 2.3.4 |
| 22 | SSH | OpenSSH 4.x (verify exact scan output) |
| 80 | HTTP | Apache (verify exact scan output) |

Note: The exact versions should be confirmed against
the original Nmap scan evidence.

## 3. Important Discovery – FTP

One of the most significant discoveries was the FTP
service running on port 21.

The service banner identified:

vsftpd 2.3.4

This version became the focus of vulnerability research.

## 4. Why Enumeration Is Important

Enumeration helps an ethical hacker understand:

- Which applications are running.
- Which versions are installed.
- Which services are exposed.
- Whether outdated software is present.
- Which vulnerabilities may be relevant.

## 5. Attacker's Perspective

An attacker may use service-version information
to search for publicly known vulnerabilities.

This demonstrates why organisations should avoid
exposing unnecessary services and should maintain
up-to-date software.

## 6. Outcome

The FTP service running vsftpd 2.3.4 was identified
as a potential vulnerability requiring further
investigation.

This discovery led to the vulnerability research
and exploitation stages.
