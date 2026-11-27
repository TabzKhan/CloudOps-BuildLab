# Day 01 - Linux Server Setup

## Objective
Set up a CentOS Stream 10 virtual machine using VMware Workstation.

## Virtual Machine Configuration

| Component | Configuration |
|---|---|
| VM Name | Linux-Server-01 |
| Operating System | CentOS Stream 10 |
| RAM | 3 GB |
| CPU | 2 Cores |
| Storage | 30 GB |
| Network | NAT |
| Installation Type | Minimal |

## Installation Progress

- [x] VMware virtual machine created
- [x] CentOS Stream 10 ISO selected
- [x] Network configured
- [x] Hostname configured
- [x] Root account disabled
- [x] Administrator user configured
- [ ] OS installation completed
- [ ] First successful login
- [ ] Network connectivity verified

## Learning Outcome

Documenting my first Linux server setup as part of CloudOps BuildLab.
## Day 1 – Installation and Initial Server Validation

### 1. Server Information
- Operating System: CentOS Stream 10
- Hostname: linux-server-01
- Username: cloudadmin
- Installation: Minimal
- Network Mode: VMware NAT

### 2. System Resource Verification
- RAM inspected using `free -h`
- Disk usage inspected using `df -h`
- Network interfaces inspected using `ip a`

### 3. Network Validation
- Network interface: ens33
- IP Address: 192.168.38.128/24
- Default Gateway: 192.168.38.2
- Gateway connectivity: Successful
- Internet connectivity: Successful
- DNS resolution: Successful

### 4. User and Privilege Management
- User: cloudadmin
- UID: 1000
- Primary Group: cloudadmin
- Supplementary Group: wheel
- Sudo privileges: Verified using `sudo -l`
- Root execution: Verified using `sudo whoami`

### 5. Commands Practiced
- whoami
- hostname
- pwd
- free -h
- df -h
- ip a
- ip route
- ping -c
- id
- groups
- sudo -l

### 6. Learning Outcome
Successfully installed CentOS Stream 10, logged in using a non-root administrative account, inspected system resources, verified network connectivity, and confirmed sudo privileges.