# Bash Scripting & Linux Fundamentals

## 1. Executive Summary
This note covers essential Linux shell environments, command-line operations, and Bash scripting fundamentals used for system administration, log analysis, and task automation in Information Assurance.

## 2. Technical Mechanics & Commands
```bash
# Filter failed SSH login attempts from authentication logs
grep "Failed password" /var/log/auth.log | awk '{print $11}' | sort | uniq -c | sort -nr
