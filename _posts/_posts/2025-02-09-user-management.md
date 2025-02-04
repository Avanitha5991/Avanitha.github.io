---
layout: post
title: "Linux User Management Commands"
date: 2025-02-09
categories: linux
---

# 👥 Linux User Management

## 🔑 Create & Manage Users
- `adduser username` → Create a new user
- `passwd username` → Set password for a user
- `usermod -aG sudo username` → Grant sudo privileges

## 👥 Group Management
- `groupadd devs` → Create a new group
- `usermod -aG devs username` → Add user to a group
- `groups username` → List user's groups

## ❌ Deleting Users
- `deluser username` → Remove a user
- `deluser --remove-home username` → Delete user and home directory

---
