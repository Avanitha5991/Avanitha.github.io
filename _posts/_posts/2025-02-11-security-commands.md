---
layout: post
title: "Linux Security & Firewall Commands"
date: 2025-02-11
categories: linux
---

# 🔐 Linux Security & Firewall Commands

## 🔍 Checking Security Logs
- `sudo cat /var/log/auth.log` → View authentication logs
- `sudo dmesg | grep "error"` → Check kernel logs for errors

## 🛡️ Firewall Management (UFW)
- `sudo ufw enable` → Enable firewall
- `sudo ufw allow 22/tcp` → Allow SSH traffic
- `sudo ufw deny 80/tcp` → Block HTTP traffic
- `sudo ufw status` → Show firewall rules

## 👤 Secure SSH Access
- `sudo systemctl restart ssh` → Restart SSH service
- `nano /etc/ssh/sshd_config` → Modify SSH settings
- `AllowUsers username` → Restrict SSH access

---
