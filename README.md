# Cybersecurity Lab: Password Auditing with Kali Linux and Medusa

## About the Project

This project was developed as part of a practical cybersecurity challenge from DIO. The main goal is to simulate controlled brute-force scenarios using Kali Linux, Medusa, and vulnerable lab environments such as Metasploitable 2 and DVWA.

The project focuses on understanding how weak authentication mechanisms can expose services to security risks and how preventive measures can reduce the impact of brute-force attacks.

This repository also serves as a technical portfolio project, documenting the learning process, the lab environment, the tools used, the risks studied, the evidence collected, and the recommended mitigation strategies.

All activities described in this repository are intended for educational purposes only and were planned to be executed in a local, controlled, and authorized laboratory environment.

## Learning Objectives

Through this project, the following cybersecurity concepts are explored:

- Understanding brute-force attacks against different services;
- Using Kali Linux in a controlled lab environment;
- Studying Medusa as a password auditing tool;
- Performing basic network scanning and service enumeration;
- Understanding authentication risks in FTP, Web, and SMB services;
- Documenting technical procedures in a clear and organized way;
- Identifying risks related to weak credentials;
- Proposing mitigation and prevention measures;
- Using GitHub as a technical portfolio for cybersecurity documentation.

## Ethical Notice

This project was performed exclusively in a local, controlled, and authorized lab environment.

No tests were executed against public systems, third-party networks, companies, institutions, or any environment without explicit permission.

The purpose of this repository is educational. It is focused on learning cybersecurity concepts, understanding risks, documenting defensive recommendations, and reinforcing the importance of ethical behavior in information security.

Any evidence, screenshots, logs, or outputs included in this repository must be sanitized before publication to avoid exposing sensitive information.

## Lab Environment

The planned lab environment includes:

- Kali Linux;
- Metasploitable 2;
- DVWA;
- VirtualBox;
- Host-only network;
- Medusa;
- Nmap.

## Lab Architecture

The environment is based on virtual machines configured in VirtualBox.

| Machine | Role |
|---|---|
| Kali Linux | Security testing and analysis machine |
| Metasploitable 2 | Vulnerable target machine |
| DVWA | Vulnerable web application for controlled testing |

The machines are configured in a host-only network to ensure that all tests are performed locally and do not affect external systems.

## Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| VirtualBox | Virtual machine management |
| Metasploitable 2 | Vulnerable target machine |
| DVWA | Vulnerable web application |
| Medusa | Password auditing tool |
| Nmap | Network scanning and service enumeration |
| GitHub | Project documentation and portfolio sharing |

## Lab Scenarios

The project is organized into three main scenarios.

### Scenario 1 — FTP

A controlled simulation of authentication testing against a vulnerable FTP service using sample usernames and passwords created only for the lab environment.

The objective of this scenario is to understand how weak credentials can expose network services and how proper security controls can reduce this risk.

### Scenario 2 — DVWA

A study of automated authentication attempts against a vulnerable web login form, focusing on understanding the risk and documenting the behavior of the application.

The objective of this scenario is to analyze how web applications can be affected by weak authentication controls.

### Scenario 3 — SMB

A study of user enumeration and password spraying concepts against an SMB service inside the controlled lab environment.

The objective of this scenario is to understand the risks associated with exposed network services, weak passwords, and insufficient account protection policies.

## Repository Structure

```text
docs/       Detailed project documentation
wordlists/  Simple sample username and password lists
images/     Screenshots from the lab environment
logs/       Sanitized outputs from the tests
```

## Security Risks Studied

This project focuses on common risks related to weak authentication and exposed services, such as:

- Weak passwords;
- Default credentials;
- Reused passwords;
- Lack of account lockout policies;
- Lack of multi-factor authentication;
- Exposed authentication services;
- Insufficient monitoring of failed login attempts;
- Poor network segmentation;
- Unnecessary services enabled;
- Outdated vulnerable systems;
- Poor password management practices;
- Misconfigured services;
- Excessive access permissions.

These risks are studied in a controlled environment to understand how they can affect the confidentiality, integrity, and availability of systems and services.

## Mitigation Measures

Some mitigation strategies studied in this project include:

- Enforcing strong password policies;
- Avoiding the use of default credentials;
- Implementing multi-factor authentication;
- Limiting failed login attempts;
- Applying account lockout policies;
- Monitoring authentication logs;
- Reviewing exposed services regularly;
- Disabling unnecessary services;
- Keeping systems and applications updated;
- Restricting access by IP address;
- Applying network segmentation;
- Using least privilege principles;
- Improving security awareness and user training.

The goal of these measures is to reduce the likelihood of successful brute-force attacks and improve the overall security posture of the environment.

## Evidence and Documentation

All screenshots and logs included in this repository must be sanitized before publication.

Sensitive information such as real passwords, personal data, public IP addresses, private credentials, or information from third-party systems must not be published.

The documentation will include:

- Lab setup description;
- Network configuration notes;
- Screenshots of the virtual environment;
- Sanitized outputs from the tests;
- Description of each test scenario;
- Risk analysis;
- Mitigation recommendations;
- Final conclusions.

The purpose of the evidence is to demonstrate the learning process and the technical understanding of the concepts, not to expose sensitive data or encourage unauthorized activity.

## Expected Results

At the end of this project, the expected results are:

- A functional cybersecurity lab using virtual machines;
- A documented understanding of brute-force risks;
- A clear explanation of how weak authentication can affect services;
- Organized evidence of the learning process;
- Sanitized technical documentation;
- A set of defensive recommendations based on the risks studied;
- A GitHub repository that can be used as a cybersecurity portfolio project.

## Project Status

In progress.

## Conclusion

This project aims to demonstrate the importance of understanding brute-force attacks in a safe and ethical way.

By using a controlled lab environment, it is possible to study how authentication weaknesses can be analyzed and, more importantly, how they can be prevented through proper security practices.

The project reinforces that cybersecurity is not only about using tools, but also about understanding risks, documenting findings, respecting ethical boundaries, and proposing responsible mitigation strategies.

Through this laboratory, the main objective is to connect theory and practice while developing a professional approach to cybersecurity documentation.
