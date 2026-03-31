# oss-audit-24MIP10018
A Capstone Project for OSS NGMC Course

# **Open Source Audit Project — MySQL**

## Student Details

* **Name:** Arunika Bag
* **Registration Number:** 24MIP10018
* **Course:** Open Source Software

---

## Chosen Software

MySQL is an open-source relational database management system widely used in web applications and part of the LAMP stack.

---

# Project Overview

This repository contains:

* 📄 Open Source Audit Report (PDF)
* 🖥️ 5 Shell Scripts demonstrating Linux and open-source concepts
* 📘 README with setup and execution steps

---

# Environment Setup

This project was developed and tested on a Linux system.

## Requirements

* Linux OS (Ubuntu / Debian / Arch recommended)
* Bash Shell
* MySQL Server
* Basic Linux utilities

---

## Install Dependencies

Run the following commands:

```bash
sudo apt update
sudo apt install mysql-server
sudo apt install lsb-release
```

For Arch Linux:

```bash
sudo pacman -S mysql
```

---

# Scripts Description

## Script 1 — System Identity Report

Displays system information such as:

* Kernel version
* Logged-in user
* Uptime
* Date and time
* Linux distribution
* OS license

 Demonstrates: variables, command substitution, echo

---

## Script 2 — FOSS Package Inspector

Checks if MySQL is installed and shows:

* Version
* License
* Developer details

Demonstrates: if-else, dpkg, grep, awk, case statement

---

## Script 3 — Disk and Permission Auditor

Analyzes system directories:

* Disk usage
* Permissions
* Ownership

Demonstrates: loops, file checks, text processing

---

## Script 4 — Log File Analyzer

Reads a log file and:

* Counts keyword occurrences (default: error)
* Displays last 5 matching lines

Demonstrates: while loop, conditionals, arguments

---

## Script 5 — Open Source Manifesto Generator

Creates a personalized manifesto by:

* Taking user input
* Generating a paragraph
* Saving it to a file

Demonstrates: user input, string handling, file writing

---

# How to Run the Scripts

##  Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/oss-audit-yourrollnumber.git
cd oss-audit-yourrollnumber
```

---

##  Step 2: Give Execution Permission

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

---

##  Step 3: Run Each Script

### Script 1

```bash
./script1.sh
```

---

### Script 2

```bash
./script2.sh
```

---

### Script 3

```bash
./script3.sh
```

---

### Script 4

```bash
./script4.sh /var/log/syslog error
```

👉 You can change keyword:

```bash
./script4.sh /var/log/syslog warning
```

---

### Script 5

```bash
./script5.sh
```

---

# Notes

* Some scripts may require **sudo privileges** (especially for logs)
* Log file paths may vary:

  * Ubuntu → `/var/log/syslog`
  * Arch → `/var/log/pacman.log`

---

# Conclusion

This project demonstrates both **theoretical understanding of open-source software** and **practical Linux skills using shell scripting**. It highlights how tools like MySQL are integrated into modern systems and how open-source principles enable collaboration and innovation.

