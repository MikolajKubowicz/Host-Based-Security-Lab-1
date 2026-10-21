# Host-Based Security — Lab 1

## Overview

This repository documents Lab 1 for CSEC 378/418 at DePaul University.

The lab focuses on Linux system administration, access control,
file permissions, authentication, and system logging using Debian Linux.

## Technologies Used

- Debian GNU/Linux 13
- Linux Command Line
- MyNETLAB
- SSH
- systemd
- journalctl
- Apache2

## Lab Objectives

### 1. Linux User and Group Management
- Create and manage Linux user accounts
- Configure user groups
- Modify group memberships
- Manage administrative privileges

### 2. File Permissions and Ownership
- Create files and directories
- Modify permissions using chmod
- Change ownership using chown
- Manage group ownership using chgrp
- Understand Linux access control

### 3. System Logging and Monitoring
- Analyze system logs using journalctl
- Investigate authentication failures
- Monitor logs in real time
- Establish SSH connections between Linux servers
- Restart and monitor Apache services
- Manage journal storage using rotation and vacuuming

## Key Linux Commands

| Command | Purpose |
|---------|---------|
| `useradd` | Create user accounts |
| `groupadd` | Create groups |
| `gpasswd` | Manage group membership |
| `groupmod` | Modify groups |
| `chmod` | Modify file permissions |
| `chown` | Change file ownership |
| `chgrp` | Change group ownership |
| `journalctl` | View system logs |
| `journalctl -f` | Monitor logs in real time |
| `journalctl -p err` | Filter error messages |
| `journalctl --disk-usage` | Check journal storage |
| `journalctl --rotate` | Rotate journal files |
| `journalctl --vacuum-size=10M` | Remove archived logs |
| `systemctl restart apache2` | Restart Apache |
| `ssh` | Connect to a remote Linux server |

## Lab Environment

- Linux Server 1: Debian 13
- Linux Server 2: Debian 13
- Virtualized environment: MyNETLAB

## Skills Demonstrated

- Linux Administration
- User Authentication
- Access Control
- File System Security
- Security Log Analysis
- SSH Remote Access
- System Monitoring
- Log Management

## Author

**Mikolaj Kubowicz**

DePaul University  
Computer Science & Cybersecurity
