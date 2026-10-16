# Virtualization & Sandboxing

## 1. Executive Summary
Overview of hypervisors and virtual machine setup to construct isolated testing environments (sandboxes) for running vulnerable applications and testing exploits safely.

## 2. Practical Configuration
```bash
# Network verification inside host-isolated testbed
ip addr show
ping -c 3 192.168.56.1
