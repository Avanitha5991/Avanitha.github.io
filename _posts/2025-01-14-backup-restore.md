---
layout: post
title: "Linux Backup & Restore Commands"
date: 2025-01-14
categories: [Linux, Commands]
---

# 🛡️ Linux Backup & Restore Commands

## 💾 Creating Backups
- `tar -cvzf backup.tar.gz /path/to/folder/` → Create a compressed backup
- `rsync -av /source/ /destination/` → Sync directories (local or remote)
- `dd if=/dev/sda of=/backup.img` → Create a disk image backup

## 🔄 Restoring Backups
- `tar -xvzf backup.tar.gz -C /restore/location/` → Extract backup
- `rsync -av /backup/ /original/` → Restore from an rsync backup

---
