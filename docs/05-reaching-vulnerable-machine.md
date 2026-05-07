# Reaching the Vulnerable Machine

## Objective

This document describes the process used to confirm that the Kali Linux machine can reach the vulnerable Metasploitable 2 machine in the host-only lab network.

This step is important because the next phases of the project depend on successful communication between the analysis machine and the vulnerable target machine.

## Lab Network

| Machine | Role | IP Address |
|---|---|---|
| Kali Linux | Analysis machine | 192.168.56.101 |
| Metasploitable 2 | Vulnerable target machine | 192.168.56.102 |

Both machines are configured in a host-only network inside VirtualBox.

## Evidence 1 — Metasploitable 2 IP Address

The Metasploitable 2 IP address was confirmed using the following command:

```bash
ifconfig
```

The IP identified in the lab was:

```text
192.168.56.102
```

![Metasploitable IP Address](images/09-metasploitable-ip-address.png)

## Evidence 2 — Connectivity Test from Kali Linux

The Kali Linux machine successfully reached the Metasploitable 2 machine using the `ping` command.

Command used:

```bash
ping 192.168.56.102
```

The response confirmed that both machines are communicating correctly in the same host-only network.

![Kali Ping Metasploitable](images/10-kali-ping-metasploitable.png)

## Result

The vulnerable machine was successfully reached from Kali Linux.

This confirms that the lab network is working and ready for the next phase: network scanning and service enumeration.

## Next Step

The next step will be to use Nmap to identify active hosts, open ports, and running services on the Metasploitable 2 machine.
