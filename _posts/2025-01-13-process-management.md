---
layout: post
title: "Linux Process Management Commands"
date: 2025-01-13
categories: [Linux, Commands]
---

# ⚙️ Linux Process Management

## 📊 Viewing Running Processes
- `ps aux` → Show all running processes
- `top` → Show live CPU/memory usage
- `htop` → Interactive process viewer

## 🛑 Killing Processes
- `kill PID` → Kill a process by ID
- `pkill -9 processname` → Kill process by name
- `killall processname` → Kill all instances of a process

## ⏳ Running Processes in Background
- `command &` → Run a command in the background
- `nohup command &` → Run a command even after logout
- `jobs` → List background jobs
- `fg %1` → Bring background job 1 to foreground

---
