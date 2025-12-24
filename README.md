# Basic Network Scanning with Nmap  
### Oasis Infobyte Internship – Task 1 Completed ✅

## Objective
The objective of this project is to perform a basic network scan using Nmap to identify open ports and running services on a target system. This task is part of the Oasis Infobyte Cyber Security Internship.

## Tool Used
- Nmap (Network Mapper)

## Target System
- Localhost (127.0.0.1)

## Scan Command Used
```bash
nmap -sV 127.0.0.1
| Port | Service               | Description                                                           |
| ---- | --------------------- | --------------------------------------------------------------------- |
| 135  | msrpc                 | Microsoft Remote Procedure Call used for Windows system communication |
| 445  | microsoft-ds          | Windows SMB service used for file and printer sharing                 |
| 902  | VMware Authentication | VMware service used for virtual machine authentication                |
| 912  | VMware Authentication | VMware service used for VM management and access                      |



Significance of Findings

Open ports indicate active services running on a system. Services like RPC and SMB are common targets for attackers if exposed to untrusted networks. Identifying these ports helps in securing systems by applying firewalls, disabling unused services, and restricting access.

Conclusion

This project successfully demonstrates basic network scanning using Nmap. It highlights the importance of identifying open ports and services to understand potential security risks.
