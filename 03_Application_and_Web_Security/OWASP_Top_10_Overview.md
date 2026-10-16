# OWASP Top Security Risks

## 1. Executive Summary
A summary of critical web application security risks defined by OWASP, focusing on vulnerability mechanisms, real-world impact, and general defensive posture.

## 2. Risk & Remediation Overview
| OWASP Category | Root Cause | Primary Mitigation |
| :--- | :--- | :--- |
| **A01: Broken Access Control** | Unenforced authorization checks | Enforce server-side role-based access control (RBAC) |
| **A02: Cryptographic Failures** | Plaintext storage / weak algorithms | Standardize on AES-256 and TLS 1.3 enforced transit |
| **A03: Injection** | Direct string concatenation into interpreters | Implement parameterized interfaces & input allowlisting |

## 3. Personal Lab Notes & Key Learnings
- **Security by Design:** Flaws in system architecture cannot be patched merely with input filters; applications must incorporate least-privilege principles at design time.
- **Defense in Depth:** Combine application-level sanitization with infrastructure isolation to minimize total breach surface.
