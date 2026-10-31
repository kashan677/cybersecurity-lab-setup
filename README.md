# VMware Virtual Machine Networking & Connectivity Lab

A hands-on networking lab demonstrating virtual machine (VM) communication, IP configuration, and connectivity testing between a Windows Host and a Kali Linux Virtual Machine using VMware Workstation.

## 🛠️ Lab Overview
This project showcases the setup and validation of network interfaces and communication between different operating systems running on a hypervisor. 

* **Host System:** Windows 10 Pro
* **Guest Virtual Machine:** Kali Linux
* **Hypervisor:** VMware Workstation

## 📋 Steps & Configuration

### 1. IP Configuration on Kali Linux
We checked the network configuration and IP addresses using the `ip a` command inside the Kali Linux terminal:
- **Interface:** `eth0`
- **IP Address Assigned:** `10.0.0.3/24`
- **MAC Address:** `00:0c:29:bb:a6:70`

### 2. Connectivity Testing (Ping Test)
From the Windows host command prompt, a connectivity test was executed to reach the virtual environment:
- **Command:** `ping 10.0.0.2`
- **Results:** 
  - Packets: Sent = 4, Received = 4, Lost = 0 (0% loss)
  - Latency: Minimum = 0ms, Maximum = 1ms, Average = 0ms

## 🚀 Key Learnings
- Configuring virtual network adapters in VMware Workstation.
- Managing IP configurations and network interfaces (`eth0`, `loopback`) in Linux.
- Utilizing ICMP echo requests (`ping`) to troubleshoot and verify host-to-VM network connectivity.

---
*Created by Kashan Rohail*




