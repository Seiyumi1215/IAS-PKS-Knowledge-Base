# Information Assurance & Security (IAS) — Personal Knowledge Base

Welcome to my **Personal Knowledge System (PKS)** for CIT312/ITL312: Information Assurance and Security. This repository serves as a curated reference guide covering virtualization, applied cryptography, web application vulnerabilities, and incident response operations.

---

## 🗂️ Knowledge Base Navigation

### 01. System & Environment Setup
* [Linux Environment & Bash Scripting](01_System_and_Environment_Setup/Linux_Environment_and_Bash.md) — Fundamental Linux CLI usage, file permissions, shell piping (`grep`/`awk`), and scripting.
* [Virtualization & Sandboxing](01_System_and_Environment_Setup/Virtualization_and_Sandboxing.md) — Configuring isolated VM networks (Host-Only vs. NAT) for safe exploit testing.

### 02. Cryptography & Secure Communications
* [Practical Cryptography & PGP](02_Cryptography_and_Secure_Comms/Practical_Cryptography_and_PGP.md) — Symmetric/asymmetric encryption principles, public-key infrastructure, and Mailvelope email signing.

### 03. Application & Web Security
* [OWASP Top 10 Overview](03_Application_and_Web_Security/OWASP_Top_10_Overview.md) — Analysis of critical web application risks.
* [SQL Injection Attacks & Defenses](03_Application_and_Web_Security/SQL_Injection_Attacks_and_Defenses.md) — In-band vs. blind payloads, DVWA testing, and parameterized queries.
* [Command Injection Mechanics](03_Application_and_Web_Security/Command_Injection_Mechanics.md) — Exploiting command chaining operators (`&`, `;`, `|`), input bypasses, and sanitization.

### 04. Incident Response & Forensics
* [Incident Handling Lifecycle](04_Incident_Response_and_Forensics/Incident_Handling_Lifecycle.md) — Structured response framework (NIST SP 800-61), root-cause analysis, and post-incident reporting.

---

## 🛠️ Key Hands-On Environments
- **DVWA (Damn Vulnerable Web Application):** Web vulnerability testing ground.
- **Mailvelope / OpenPGP:** Browser-based message encryption and signing.
- **Virtualization:** VirtualBox / VMware host-isolated environments.

---

## 📝 Core Key Takeaways
1. **Input Validation is Paramount:** Unchecked input is the leading root cause of high-severity vulnerabilities like SQLi and OS Command Injection.
2. **Key Protection Matters:** Asymmetric encryption protects communication privacy, provided private keys remain confidential.
3. **Isolated Environments:** Always perform penetration testing and vulnerability analysis within isolated virtual environments.
