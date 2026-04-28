# VAPT Report — Metasploitable 2
## Ports 514 (RSH) & 2049 (NFS)

**Author:** Faysal Amin
**Institute:** Creative IT Institute, Dhaka
**Date:** April 2026

---

## Overview
Complete Vulnerability Assessment and Penetration Testing 
report targeting Metasploitable 2 virtual machine.

## Target
- Machine: Metasploitable 2
- IP: 192.168.3.129
- Ports: 514 (RSH) and 2049 (NFS)

## Tools Used
- Nmap 7.99
- Metasploit Framework
- RSH Client
- NFS-Common / Mount
- SSH-Keygen

## Findings
| Port | Service | Severity | Result |
|------|---------|----------|--------|
| 514 | RSH | Critical (10.0) | Root Shell |
| 2049 | NFS | Critical (10.0) | Root SSH Backdoor |

## Files
- VAPT_Report_Faysal_Amin_Port514_2049.docx

## Disclaimer
This assessment was conducted in an isolated lab 
environment for educational purposes only.
All testing was performed on Metasploitable 2 — 
a purposefully vulnerable machine.
Never perform penetration testing without 
explicit written permission.
