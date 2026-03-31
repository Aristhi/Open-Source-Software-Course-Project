# The Open Source Audit: Python & Linux Automation
**Capstone Project for Open Source Software (OSS)**

## Student Information
* **Student Name:** Arnima Awasthi
* **Registration Number:** 24BA110813
* **Chosen Software :** Python

## Project Description
This project is a comprehensive audit of **Python** as an open-source software. It explores the evolution of Python from its inception by Guido van Rossum to its current role as a cornerstone of modern AI and Data Science. The project covers technical aspects including the **PSF License**, comparison with proprietary alternatives, and practical Linux system administration using shell scripting.

---

## Script Descriptions
This repository contains five automation scripts designed for a Linux environment:

1.  **System Identity Report**: Displays the current Linux kernel version, active user, and system uptime.
2.  **FOSS Package Inspector**: Uses `dpkg` and `grep` to verify the installation of specific open-source packages (like Python) and extract their metadata.
3.  **Disk & Permission Auditor**: Automatically inspects critical system directories (like `/etc` and `/var/log`) to check for disk usage and file permissions.
4.  **Log File Analyzer**: A diagnostic tool that reads log files line-by-line to count occurrences of the keyword "error."
5.  **Open Source Manifesto Generator**: An interactive script that captures developer input on software freedom and exports a formatted manifesto to a `.txt` file.

---

## Prerequisites & Dependencies
To run these scripts, you will need:
* **Operating System:** Linux (Ubuntu/Debian recommended) or WSL (Windows Subsystem for Linux).
* **Shell:** Bash (standard in most Linux distributions).
* **Dependencies:** * `python3` (for the audit context).
    * `dpkg` (pre-installed on Debian-based systems).
    * Standard GNU utilities (`grep`, `chmod`, `awk`).

---

## Instructions to Run the Scripts

Follow these steps exactly to execute the scripts on your Linux terminal:

### 1. Grant Execution Permissions
By default, Linux may block scripts from running. You must grant permission using `chmod`:
```bash
# To grant permission to all scripts at once:
chmod +x *.sh

# Or to a specific script:
chmod +x script1.sh
2. Execute the Scripts
Run the scripts using the ./ prefix:

For Script 1, 2, 3, and 5:

Bash
./script1.sh
For Script 4 (Log Analyzer):
This script requires a file path as an argument.

Bash
./script4.sh path/to/your/logfile.log
File Structure
OSSCapstoneProject_24BAI10813.pdf: Complete technical report.

script1.sh through script5.sh: Linux automation shell scripts.

README.md: Project documentation (this file).

