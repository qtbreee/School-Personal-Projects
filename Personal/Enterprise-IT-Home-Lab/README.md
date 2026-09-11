# Enterprise IT Home Lab

## Overview

This project documents my progress building an enterprise-style IT environment using VMware Workstation and Windows Server 2022.

The purpose of this lab is to develop practical experience with Windows Server administration, Active Directory, networking, user management, troubleshooting, and PowerShell.

## Technologies

- VMware Workstation
- Windows Server 2022
- Windows 10/11
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- PowerShell

## Current Progress

## Step 1: Windows Server Installation

I created a virtual machine in VMware Workstation and installed Windows Server 2022.

![Windows Server installation](Server-Installation.jpg)

## Step 2: VMware Tools

I installed VMware Tools to improve the virtual machine’s performance and functionality.

![VMware Tools installed](vmware-tools.png)

## Step 3: Network Configuration

I reviewed the server’s network settings and IP configuration.

![Network settings](network-settings.jpg)

![IP configuration](ip-configuration.jpg)

## Step 4: Connectivity Testing

I used the `ping 8.8.8.8` command to test external network connectivity. The successful responses confirmed that the server could communicate outside the local network.

![Successful ping test](connectivity-test.jpg)

## Next Steps

- Configure a static IP address
- Install Active Directory Domain Services
- Configure DNS and DHCP
- Create users and groups
- Join a Windows client to the domain
- Configure Group Policy
- Technical troubleshooting
- System documentation

## Project Status

This project is currently in progress. New configurations, screenshots, troubleshooting notes, and PowerShell scripts will be added as the lab develops.
