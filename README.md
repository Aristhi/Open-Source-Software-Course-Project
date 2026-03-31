# Open-Source-Software-Course-Project
**STUDENT DETAILS**

Arnima Awasthi 

Registration Number: 24BA110813 

Chosen Software : Python

__Project Overview__
This project is a capstone report for the Open Source Software (OSS) course. It explores the history and practical applications of Python within the open-source ecosystem. The audit includes a deep dive into the Python Software Foundation License (PSFL), comparison with proprietary software like MATLAB, and an investigation into Python's footprint on Linux systems.

__Key Components__

OSS Analysis: A in-depth look at Python's origin, starting with Guido van Rossum in 1989 , and its evolution into a foundation for AI and Data Science.

Linux Integration: Documentation on installing and managing Python using the apt package manager and auditing the Linux filesystem hierarchy.

Security & Permissions: Investigation of system processes, memory usage, and file permissions (e.g., /usr/bin/python3) to ensure administrative transparency.

FOSS Ecosystem: Analysis of how Python interacts with other open-source tools like the GNU C Library (glibc), OpenSSL, and the LAMP stack.

__Automation Scripts__
The project includes five specialized shell scripts demonstrating Linux automation:

System Identity Report: Displays kernel version, user, and system uptime.

FOSS Package Inspector: Uses dpkg and grep to verify software installations and metadata.

Disk and Permission Auditor: Automates inspection of critical paths like /etc and /var/log.

Log File Analyzer: Scans log files for specific keywords (like "error") using loops and grep.

Manifesto Generator: An interactive script that captures developer viewpoints on software freedom and exports them to a text file.

__Files in this Repository__
OSSCapstoneProject_24BAI10813.pdf: The full technical audit report.

scripts/: A folder containing the .sh automation files.

