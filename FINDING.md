# Scan Analysis Report

## Scan Summary
- **Date:**   23-june-2025
- **IP Range Scanned:** 172.17.0.0/16
- **Total Hosts Discovered:** 32768

**Open Ports Identified** 
## Critical Findings

| IP Address   | Port | Service       | Risk Level | Notes                     |
|--------------|------|---------------|------------|---------------------------|
| 172.17.0.1   | 22   | SSH           | High       | Default credentials?      |
| 172.17.0.1   | 80   | HTTP          | Medium     | Unencrypted web traffic   |
| 172.17.0.2   | 445  | SMB           | Critical   | Potential EternalBlue vuln|
| 172.17.0.3   | 3389 | RDP           | High       | Open remote desktop       |
| 172.17.1.100 | 5432 | PostgreSQL    | High       | No authentication         |
| 172.17.2.50  | 5900 | VNC           | Critical   | Unencrypted screen sharing|
| 172.17.0.255 | 161  | SNMP          | Medium     | Public community string   |
