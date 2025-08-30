# Network Security Groups (NSGs) and Inspecting Network Protocols Using Wireshark

<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

This tutorial demonstrates how to observe network traffic to and from Azure Virtual Machines using Wireshark, as well as how to experiment with Network Security Groups (NSGs).

---

## Video Demonstration

- [Network Security Groups and Inspecting Network Protocols with Wireshark]

---

## Environments and Technologies Used

- Microsoft Azure Windows and Linux Virtual Machines  
- Remote Desktop Connection  
- Powershell and Various Command-Line Tools  
- Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)  
- Wireshark (packet analyzer/network sniffer)  

## Operating Systems Used

- Windows 10 Pro  
- Linux Ubuntu  

---

## High-Level Steps

- Observe ICMP Traffic (Internet Control Message Protocol)  
- Configure a Firewall (Network Security Group)  
- Observe SSH Traffic (Secure Shell)  
- Observe DHCP Traffic (Dynamic Host Configuration Protocol)  
- Observe DNS Traffic (Domain Name System)  
- Observe RDP Traffic (Remote Desktop Protocol)  

---

## Actions and Observations

### Initial Setup

Ensure both Virtual Machines are running. Log in to the Windows VM using Remote Desktop Connection with its public IP and credentials.  

<p>
<img src="https://github.com/user-attachments/assets/56c42ac0-9ee8-43c4-8c9e-7e1b0becaf8f" /> 
<img src="https://github.com/user-attachments/assets/b9549912-ceeb-422f-ad4d-6562dcab6179" />
</p>

---

### Observe ICMP Traffic

1. In Wireshark, type `icmp` in the filter bar to isolate ICMP traffic.  
2. Open PowerShell on the Windows VM and run:  

