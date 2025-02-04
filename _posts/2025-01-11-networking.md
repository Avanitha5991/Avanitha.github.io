---
layout: post
title: "Linux Networking & Troubleshooting Commands"
date: 2025-01-11
categories: [Linux, Commands]
---

# 🌐 Linux Networking & Troubleshooting Commands

## 🖥️ Checking Network Status
- `ip a` → Show IP addresses
- `ifconfig` → Display network interfaces
- `netstat -tulnp` → List open ports & services
- `ss -tulnp` → Alternative to `netstat`

## 🛜 Checking Connectivity
- `ping google.com` → Check internet connectivity
- `traceroute google.com` → Trace network hops to a destination
- `curl ifconfig.me` → Get your public IP address

## 🔍 Analyzing Traffic
- `tcpdump -i eth0` → Capture network packets on `eth0`
- `nmap -sV 192.168.1.1` → Scan a local network for open ports

---
