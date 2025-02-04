---
layout: post
title: "Linux Performance Monitoring & Optimization"
date: 2025-01-08
categories: [Linux, Commands]
---

# 🚀 Linux Performance Monitoring

## 🖥️ Checking System Resource Usage
- `htop` → Interactive system monitor
- `free -m` → Show RAM usage
- `vmstat 1` → Show CPU, memory, I/O stats
- `iostat -x 1` → Monitor disk performance

## ⚡ Optimizing Performance
- `echo 3 > /proc/sys/vm/drop_caches` → Clear memory cache
- `nice -n 10 ./script.sh` → Run a process with lower priority
- `ulimit -n 100000` → Increase file descriptor limit

---
