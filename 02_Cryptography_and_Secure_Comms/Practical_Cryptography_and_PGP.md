# Encryption Fundamentals & Mailvelope PGP

## 1. Executive Summary
A guide to symmetric/asymmetric cryptography, public key infrastructure (PKI), and end-to-end browser-based email encryption using OpenPGP via Mailvelope.

## 2. Practical Syntax & Workflow
```bash
# Generating GPG keypair via command line (CLI alternative to Mailvelope)
gpg --full-generate-key
gpg --export -a "User Name" > publickey.asc
