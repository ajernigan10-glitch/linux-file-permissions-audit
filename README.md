# Linux File Permissions Audit & Remediation

## Overview
This project demonstrates practical Linux access control auditing and remediation using command-line tools. The objective was to identify permission misconfigurations and enforce the principle of least privilege in a research environment.

## Tools Used
- Linux (Bash)
- ls -la
- chmod (symbolic and numeric modes)

## Key Skills Demonstrated
- File permission auditing
- Interpreting 10-character permission strings
- Securing hidden files
- Directory access restriction
- Access control hardening

## Commands Used

```bash
ls -la
chmod o-w project_k.txt
chmod 440 .project_x.txt
chmod 700 drafts
