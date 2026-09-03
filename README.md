# Enterprise-IT-Support-Homelab
Enterprise IT Support Homelab demonstrating Windows Server, Active Directory, DNS, DHCP, Group Policy, PowerShell and real-world IT troubleshooting.
Enterprise IT Support Homelab

Project Overview

This project simulates a small enterprise IT environment and demonstrates practical IT Support and System Administration skills.

The lab was designed to practise common IT Support activities including user and account management, Windows troubleshooting, network diagnostics, permissions, Group Policy and incident resolution.

Objectives

* Build a virtual Windows enterprise environment
* Configure Active Directory Domain Services
* Configure DNS and DHCP
* Create and manage users and security groups
* Join Windows client machines to the domain
* Configure Group Policy
* Configure shared folders and permissions
* Troubleshoot common Windows and network issues
* Automate diagnostic tasks using PowerShell
* Document incidents using a structured troubleshooting process

Technologies

* Windows Server
* Windows 11
* Active Directory
* DNS
* DHCP
* Group Policy
* PowerShell
* Windows Event Viewer
* TCP/IP Networking
* VirtualBox / VMware

Lab Architecture

The environment consists of a Windows Server acting as the domain controller and a Windows 11 client connected to the domain.

Environment

Component	Configuration
Domain Controller	Windows Server
Client	Windows 11
Domain	abctech.local
Directory Service	Active Directory
DNS	Windows DNS
DHCP	Windows DHCP
Network	192.168.10.0/24
Automation	PowerShell
Virtualisation	VirtualBox / VMware

Active Directory

The following organisational structure was created:

ABC Technologies
│
├── IT
├── HR
├── Finance
└── Management

Users and security groups were created to simulate a real business environment.

Troubleshooting Scenarios

The lab includes simulated incidents such as:

1. Password reset
2. Account lockout
3. DNS failure
4. Network connectivity failure
5. File permission problem
6. Group Policy issue
7. Printer problem
8. Low disk space
9. Windows service failure
10. Slow computer

Each incident follows a structured troubleshooting process:

Identify Problem
       ↓
Gather Information
       ↓
Perform Diagnostics
       ↓
Identify Root Cause
       ↓
Apply Resolution
       ↓
Test Solution
       ↓
Document Incident

PowerShell Automation

PowerShell scripts were developed to assist with common IT Support tasks including:

* System health checks
* Network diagnostics
* Disk space checks
* Windows service checks

Skills Demonstrated

* Windows Administration
* Active Directory
* DNS & DHCP
* TCP/IP Networking
* Group Policy
* PowerShell
* User & Access Management
* Troubleshooting
* Incident Management
* Root Cause Analysis
* Technical Documentation

Disclaimer

This is a personal homelab project created for learning and portfolio purposes. No real company systems or user data are used.
