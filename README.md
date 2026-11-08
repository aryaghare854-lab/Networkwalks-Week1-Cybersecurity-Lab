# Week 1: Cybersecurity Lab Setup

As part of my Cybersecurity program at Networkwalks (Batch B084), I completed my first weekly task: setting up a cybersecurity testing lab using VirtualBox and Kali Linux.

## Lab Overview

The objective was to create a virtual environment for practicing cybersecurity and penetration testing in a controlled lab.

### Tools Used

- Oracle VirtualBox
- Kali Linux
- 7-Zip

### Lab Configuration

| Component | Configuration |
|---|---|
| Virtualization Software | VirtualBox |
| Operating System | Kali Linux |
| Network Type | NAT Network |
| Network Subnet | 10.0.0.0/24 |
| Kali IP Address | 10.0.0.2/24 |
| Default Gateway | 10.0.0.1 |

## Lab Setup Steps

### 1. Kali Linux Virtual Machine

The Kali Linux virtual machine was imported into VirtualBox and started successfully.

### 2. VirtualBox NAT Network Configuration

A custom NAT Network was created in VirtualBox using the `10.0.0.0/24` subnet. This allows virtual machines connected to the same network to communicate with each other and access the internet.

### 3. Kali Linux Desktop

The Kali Linux desktop was successfully launched inside VirtualBox, confirming that the virtual machine was running.

### 4. Kali Linux Network Configuration

The network configuration was verified using the `ip a` command. Connectivity was tested by pinging the NAT gateway and a public IP address.

## What I Learned

- Setting up and configuring a virtual machine.
- Understanding NAT and NAT Network.
- Configuring IPv4 addresses, gateways, and DNS.
- Verifying network connectivity.
- Creating VM snapshots for recovery.

## Outcome

Successfully configured a Kali Linux virtual machine with network connectivity, ready for future cybersecurity practicals.


---

## Additional Work – Wireshark SOC Project

As part of my Networkwalks Cybersecurity Program (Batch B084), I completed an additional Wireshark SOC Project consisting of 6 practical labs, each containing 10 investigation tasks.

### Tools Used
- Wireshark
- PCAP Network Captures
- TCP/IP and HTTP Protocol Analysis

### 1. Wireshark SOC Labs

| Lab | Investigation | Score | Result |
|---|---|---:|---|
| Lab 3 | Identify the Attacker's IP | 100% | [View Lab 3 Result](./wireshark-labs/Lab%203%20Result%20-%20Arya%20Ananda%20Ghare.png) |
| Lab 4 | Follow TCP Stream – Part 1 | 90% | [View Lab 4 Result](./wireshark-labs/Lab%204%20Result%20-%20Arya%20Ananda%20Ghare.png) |
| Lab 5 | Follow TCP Stream – Part 2 | 90% | [View Lab 5 Result](./wireshark-labs/Lab%205%20Result%20-%20Arya%20Ananda%20Ghare.png) |
| Lab 6 | HTTP Plain Text Credentials | 100% | [View Lab 6 Result](./wireshark-labs/Lab%206%20Result%20-%20Arya%20Ananda%20Ghare.png) |
| Lab 7 | Catch the Brute Force Attacker | 100% | [View Lab 7 Result](./wireshark-labs/Lab%207%20Result%20-%20Arya%20Ananda%20Ghare.png) |
| Lab 8 | Catch the Call Scammer (VoIP) | 100% | [View Lab 8 Result](./wireshark-labs/Lab%208%20Result%20-%20Arya%20Ananda%20Ghare.png) |

**Overall Lab Score: 93.33%**

### 2. Wireshark Quizzes

| Quiz | Score | Result |
|---|---:|---|
| Wireshark Quiz | 100% | [View Wireshark Quiz Result](./wireshark-quizzes/Screenshot%202026-11-07%20224939.png) |
| Advanced Wireshark Quiz | 80% | [View Advanced Wireshark Quiz Result](./wireshark-quizzes/Screenshot%202026-11-08%20111525.png) |

**Overall Quiz Score: 90%**

### 3. Skills Practiced

- Network packet capture and traffic analysis.
- Identifying suspicious IP addresses and attackers.
- Wireshark display filters.
- TCP stream reconstruction.
- HTTP plaintext credential analysis.
- Brute-force attack detection.
- VoIP traffic investigation.
- Network protocol analysis.

### 4. Learning Outcome

Gained hands-on experience in network traffic analysis, packet inspection, network forensics and SOC investigation techniques through practical Wireshark exercises.

**Platform:** Networkwalks  
**Program:** Cybersecurity Internship  
**Batch:** B084


## Acknowledgment

Thank you to Sir Waqas Karim (CCIE) and the Networkwalks team for the guidance and support.
