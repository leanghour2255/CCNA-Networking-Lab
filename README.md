# Cisco CCNA Networking Lab Portfolio

> **Status:** In Progress — actively adding labs as I progress through the CCNA 200-301 curriculum.

A hands-on collection of enterprise networking labs designed, configured, and verified in Cisco Packet Tracer. Built as part of my CCNA certification preparation (following Jeremy's IT Lab), this repository documents foundational Layer 2 and Layer 3 network engineering skills.

## What Each Lab Includes
* **Topology File (`.pkt`):** Ready-to-open Cisco Packet Tracer lab file.
* **Device Configurations:** Running configs and key Cisco IOS CLI commands.
* **Verification:** Topology diagrams and CLI outputs (`show ip route`, `show ip interface brief`, `ping`) confirming end-to-end connectivity.

## Core Networking Labs

| # | Lab Project | Key Skills Demonstrated |
| :--- | :--- | :--- |
| 01 | [Cisco IOS CLI Basics](./01-Cisco-IOS-CLI-Basics) | Device hardening, console/enable passwords, MOTD banners, NVRAM config management |
| 02 | [IPv4 Addressing](./02-IPv4-Addressing) | Interface IP assignment, subnet mask configuration, Layer 3 connectivity testing |
| 03 | [Interface Configuration](./03-Interface-Configuration) | Port speed/duplex tuning, interface descriptions, unused port hardening |
| 04 | [Static Routing](./04-Static-Routing) | Manual static route configuration, default routes (`0.0.0.0/0`), end-to-end reachability |
| 05 | [Subnetting & VLSM](./05-Subnetting-VLSM) | Variable Length Subnet Masking, IP address space optimization, multi-subnet routing |

## Tools & Environment
* **Network Simulation:** Cisco Packet Tracer 
* **Version Control:** Git & GitHub (Windows PowerShell / VS Code)