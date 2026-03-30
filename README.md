# Log Archive Tool

A simple CLI tool to compress and archive logs automatically, reducing disk usage and keeping systems clean without manual intervention.

---

## 🚀 Overview

This project is based on the Log Archive Tool idea from roadmap.sh:
https://roadmap.sh/projects/log-archive-tool

The tool allows you to:
- Compress logs from a given directory
- Store them in a timestamped `.tar.gz` archive
- Keep your system organized and prevent disk space issues

Designed for Linux environments and automation (e.g., cron jobs).

---

## ⚙️ Features

- Compress logs into `.tar.gz` format
- Archive files with timestamp (e.g. `logs_archive_20240330_120301.tar.gz`)
- Simple CLI usage
- Lightweight and dependency-free (pure Bash)

---

## 📦 Installation

```bash
git clone https://github.com/4ntoniomj/Log_Archive_Tool.git
cd Log_Archive_Tool
chmod +x log-archive
```

---
## ▶️ Usage
```bash
./log-archive <destination-path-without-name> <source-path>
```
