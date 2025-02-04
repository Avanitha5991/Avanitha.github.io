---
layout: post
title: "Linux Terminal Productivity Tips & Tricks"
date: 2025-01-10
categories: [Linux, Commands]
---

# 🚀 Linux Terminal Productivity Tips & Tricks

## ⌨️ Keyboard Shortcuts
- `Ctrl + R` → Reverse search command history
- `Ctrl + U` → Clear the command line before the cursor
- `Ctrl + L` → Clear terminal screen (same as `clear`)
- `Ctrl + Shift + T` → Open new tab in terminal
- `Ctrl + A` → Move to beginning of line
- `Ctrl + E` → Move to end of line
- `Alt + .` → Insert last argument from the previous command

## 🏃 Running Commands Faster
- `!!` → Run the last command again
- `!$` → Get the last argument of the last command
- `sudo !!` → Rerun the last command as root
- `history | grep keyword` → Search command history

## 🔍 Finding Files Quickly
- `find / -name "filename"` → Find a file by name
- `locate filename` → Faster file search (requires `updatedb`)
- `grep -rnw '/path/' -e 'text'` → Search for text inside files

---
