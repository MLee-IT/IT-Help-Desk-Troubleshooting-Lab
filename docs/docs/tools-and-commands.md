# IT Tools and Commands

## Overview

This document describes common Windows tools and command-line utilities used throughout the IT Help Desk Troubleshooting Lab.

## Command-Line Tools

### ipconfig

**Purpose:**
Used to view and troubleshoot a computer's network configuration.

**Example command:**
'ipconfig'

**Common information displayed:**
- IPv4 address
- Subnet mask
- Default gateway

### ipconfig /release

**Purpose:**
Releases the computer's current DHCP-assigned IP address.

**Example command:**
'ipconfig /release'

**Common information displayed:**
Used when troubleshooting IP configuration problems.

### ipconfig /renew

**Purpose:**
Requests a new IP address from the DHCP server.

**Example command:**
'ipconfig /renew'

**Common information displayed:**
Can help when a computer is unable to obtain or maintain a valid IP configuration.

### ipconfig /flushdns

**Purpose:**
Clears the local DNS resolver cache.

**Example command:**
'ipconfig /flushdns'

**Common information displayed:**
Can help troubleshoor DNS resolution problems.

### ping

**Purpose:**
Tests network connectivity between the computer and another device or IP address.

**Example command:**
'ping 8.8.8.8'

A technician can also test a hostname:

'ping google.com'

**Troubleshooting use:**
Comparing an IP-address test with a hostname test can help identify potential DNS-related problems.

## Windows Troubleshooting Tools

### Task Manager

**Purpose:**
Used to investigate system performance and running processes.

**Can be used to review:**

- CPU usage
- Memory usage
- Disk usage
- Running applications
- Background processes
- Startup applications

### Device Manager

**Purpose:**
Provides information about installed hardware and device drivers.

**Can be used to:**

-Identify hardware problems
- Review device status
- Check for warning indicators
- Review driver information
- Troubleshoot connectede hardware

### Event Viewer

**Purpose:**
Provides access to Windows system and application logs.

**Can help investigate:**

- System crashes
- Application errors
- Hardware-related events
- Service failures
- Unexpected system behavior

### Windows Security

**Purpose:**
Provides built-in Windows security and protection features.

**Can be used to:**

- Check for available updates
- Review update errors
- Install updates
- Troubleshoot update problems
- Confirm that the system is up to date

### Windows Storage Settings

**Purpose:**
Used to identify how disk space is being used.

**Can be used to review:**

- Temporary files
- Applications
- Downloads
- System files
- Recycle Bin contents
- Available storage

## Networking Tools and Concepts

### DHCP

**Full name:**
Dynamic Host Configuration Protocol

**Purpose:**
Automatically provides network configuration information to devices.

**Common information provided:**

- IP address
- Subnet Mask
- Default gateway
- DNS server information

**Troubleshooting relevance:**
DHCP-related problems can prevent a computer fromo communicating properly on a network.

### DNS

**Full name:**
Domain Name System

**Purpose:**
Translates domain names into IP addresses.

**Example:**
'google.com -> IP address'

**Troubleshooting relevance:**
DNS troubleshooting can help identify situations where a computer has network connectivity but cannot properly access websites or other hostname-based resouces.

## Printing

### Print Spooler

**Purpose:**
The Windows Print Spooler service manages print jobs and communication with printers.

**Troubleshooting use:**
Restarting the Print Spooler can help resolve certain printing problems involving stuck or failed print jobs.

## Troubleshooting Principle

Tools and commands should be used to gather evidence and isolate the cause of an issue rather than simply applying random fixes.

### General Process

Observe -> Test -> Analyze -> Resolve -> Verify -> Documents