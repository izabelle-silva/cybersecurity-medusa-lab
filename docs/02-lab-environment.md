# Lab Environment

## Objective

This document describes the virtual lab environment used in the cybersecurity project.

## Tools and Platforms

The lab environment is planned with the following tools:

- VirtualBox;
- Kali Linux;
- Metasploitable 2;
- DVWA;
- Medusa;
- Nmap;
- GitHub.

## Virtual Machines

| Machine | Purpose |
|---|---|
| Kali Linux | Security testing and analysis machine |
| Metasploitable 2 | Vulnerable target machine |
| DVWA | Vulnerable web application for controlled testing |

## Network Configuration

The lab is designed to use a host-only network.

This configuration allows communication between the virtual machines while keeping the tests isolated from external systems.

## Security Precautions

The following precautions must be followed:

- Use only local virtual machines;
- Do not test public IP addresses;
- Do not use real credentials;
- Do not publish sensitive information;
- Sanitize screenshots and logs before uploading them to GitHub;
- Keep the project focused on educational and defensive purposes.

## Current Status

- VirtualBox installed;
- Kali Linux configured;
- Target vulnerable machine to be configured;
- Evidence and logs to be added later.
