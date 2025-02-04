---
layout: post
title: "Linux Disk Management Commands"
date: 2025-01-04
categories: [Linux, Commands]
---

# 💾 Linux Disk Management Commands

## 📝 Checking Disk Usage
- `df -h` → Show disk space usage in human-readable format
- `du -sh /folder/` → Show size of a folder
- `lsblk` → List all storage devices
- `fdisk -l` → Show partition information
- `mount /dev/sdb1 /mnt` → Mount a drive

## 🔍 Formatting & Managing Partitions
- `mkfs.ext4 /dev/sdb1` → Format disk with ext4 filesystem
- `fsck /dev/sdb1` → Check and repair filesystem errors
- `blkid` → Show UUID of storage devices

## 🚀 Automount Drives
- Edit `/etc/fstab`:
