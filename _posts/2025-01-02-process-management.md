---
layout: post
title: "Linux Process Management"
date: 2025-01-02
categories: [Linux, Commands]
---

# 🖥️ Linux Process Management

## 🔍 Viewing Processes
- `ps aux` → List all running processes
- `top` → Interactive process monitor
- `htop` → Advanced process viewer

## ❌ Killing Processes
- `kill <PID>` → Kill process by ID
- `killall <name>` → Kill all processes with a specific name
- `pkill -9 <name>` → Force kill process

## 🎭 Running Background Jobs
- `nohup command &` → Run command in background
- `jobs` → List background jobs
- `fg %1` → Bring job 1 to foreground
- `bg %1` → Resume job in background

---
