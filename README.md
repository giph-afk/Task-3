Vulnerability Scan Using Nessus Essentials- Task 3 
Overview
This repository contains the deliverables for Task 3 of my cybersecurity internship.
The objective of this task was to perform a basic vulnerability assessment on a VulnHub virtual machine by installing Nessus Essentials on Kali Linux, configuring the scanner, running a full scan, and documenting vulnerabilities, remediations, and notes from the Nessus report.
All screenshots have been sanitized for public sharing.

Workflow Summary
-Downloaded Nessus Essentials from the official Tenable website
-Installed the .deb package on Kali Linux
-Activated Nessus using the free Essentials key
-Started the Nessus service
-Accessed the Nessus GUI
-Waited for plugins to download and initialize
-Identified target machine using
-Created a Basic Network Scan targeting the VulnHub machine
-Launched the scan and reviewed:
  -Vulnerabilities
  -Remediations
  -Notes
  -Documented critical, high, medium vulnerabilities and recommendations

Reasoning Behind Approach
The chosen methodology aligns with standard vulnerability assessment practices:
-Nessus Essentials provides free but professional-grade scanning capabilities
-Identifying the correct host IP ensures accurate targeting inside VirtualBox
-Running a Basic Network Scan is appropriate for a beginner-level local assessment
-The VulnHub machine is intentionally vulnerable, making it suitable for controlled testing
-This approach ensures a safe, realistic, and repeatable vulnerability-scanning workflow.

Key Findings
From the Nessus Essentials scan:
Total Vulnerabilities: 34
Critical: 8
High: 2
Medium: 3
Low: 0
Info: 21
Critical Issues Identified

Repository Contents
Task3.docx → Full vulnerability assessment report
README.md → This documentation

Tools Used
-Nessus Essentials (Tenable) — vulnerability scanning
-VirtualBox — virtualization
-Kali Linux — scan host
-VulnHub VM — scan target
-Terminal — network discovery

Notes
-The target VM was intentionally vulnerable
-No real production systems or sensitive networks were scanned
-Work performed strictly for educational and testing purposes
