# 🛡️ NETWORK SCAN USING ZENMAP

[![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Reconnaissance-red)](#)
[![Nmap](https://img.shields.io/badge/Nmap-Network_Scanning-blue)](#)
[![Zenmap](https://img.shields.io/badge/Zenmap-GUI_for_Nmap-0066CC)](#)
[![Kali Linux](https://img.shields.io/badge/Kali_Linux-Security_Platform-557C94)](#)
[![Linux](https://img.shields.io/badge/Linux-Command_Line-FCC624)](#)
[![Networking](https://img.shields.io/badge/Networking-Network_Scanning-green)](#)
[![Reconnaissance](https://img.shields.io/badge/Reconnaissance-Information_Gathering-orange)](#)
[![Port Scanning](https://img.shields.io/badge/Port_Scanning-Network_Enumeration-blue)](#)
[![Service Detection](https://img.shields.io/badge/Service_Detection-Enumeration-purple)](#)
[![Ethical Hacking](https://img.shields.io/badge/Ethical_Hacking-Authorized_Testing-red)](#)
[![VirtualBox](https://img.shields.io/badge/VirtualBox-Lab_Environment-blue)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Project_Documentation-black)](#)

## Project Overview

This project is a hands-on lab focused on local network discovery and host enumeration using **Zenmap**, the official GUI for **Nmap**. Zenmap is widely used by cybersecurity professionals and ethical hackers to discover hosts, scan ports, detect services, and visualize network topology.

The lab walks through installing Zenmap, identifying a local subnet, scanning it for live hosts, recording their IP and MAC addresses, and exporting a visual topology map 

## Objectives

- Install and configure Zenmap on a Windows PC
- Identify the local IP address and LAN subnet
- Perform host discovery to find live devices on the network
- Determine the number of live hosts on the subnet
- Record the IP addresses of all live hosts
- Record the MAC addresses of all live hosts
- Generate and export a visual network topology map

## Tools Used

| Tool | Purpose |
|------|---------|
| **Zenmap** (Nmap GUI) | Network scanning and topology visualization |
| **Nmap** | Underlying scan engine (ping scan / host discovery) |
| **Windows CMD** (`ipconfig`) | Identify local IP address, subnet mask, and MAC address |

simulating the reconnaissance phase of a penetration test or network audit.
  
## Skills Demonstrated

- Network reconnaissance and host discovery
- Reading and interpreting IPv4 addressing and subnet masks
- Translating GUI scan actions into equivalent Nmap CLI commands
- Analyzing Nmap scan output (hosts up, latency, MAC vendor info)
- Visualizing and documenting network topology
- Exporting scan results/reports for documentation purposes

## Lab Environment

- **OS:** Windows 10
- **Scanning Tool:** Zenmap (bundled with Nmap 7.91 and Npcap)
- **Network:** Local LAN subnet â€” `10.0.0.0/24` (instructor's demo network; actual subnet will vary by environment)
- **Scan Profile Used:** Ping scan (`nmap -sn <subnet>`)

 Only scan networks you own or have explicit permission to test.

##  Methodology

1. **Setup** Download and install Zenmap from the official Nmap website.
2. **Reconnaissance of own host** Use `ipconfig` to determine the local IP address, subnet mask, and default gateway, deriving the LAN subnet range.
3. **Host discovery** Run a Ping scan against the full subnet in Zenmap to identify which hosts are up.
4. **Data collection** Extract the count, IP addresses, and MAC addresses of all live hosts from the Nmap output.
5. **Visualization** Use Zenmap's Topology tab to view a graphical map of discovered hosts and export it as a PDF for reporting.





