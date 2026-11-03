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

## Acknowledgment

Thank you to Sir Waqas Karim (CCIE) and the Networkwalks team for the guidance and support.
