# Linux SSH Hardening

## Overview

This project demonstrates SSH hardening on a Rocky Linux server.

The goal was to improve the security of remote administration by disabling direct root access, changing the default SSH port, restricting user access, configuring session timeouts, and troubleshooting SELinux restrictions.

---

## Skills Demonstrated

- Linux Administration
- SSH Hardening
- SELinux Troubleshooting
- Firewalld Administration
- Systemd
- User Access Control
- Security Hardening
- Log Analysis

---

## Environment

| Component | Value |
|------------|---------|
| OS | Rocky Linux 9 |
| Service | OpenSSH |
| Firewall | firewalld |
| SELinux | Enforcing |

---

## Objectives

- Disable direct root login
- Change SSH port from 22 to 2278
- Restrict SSH access to approved users
- Configure idle session timeout
- Open custom SSH port in firewalld
- Troubleshoot SELinux port binding issues
- Verify remote connectivity
