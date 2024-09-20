# reme# Home Network Vulnerability Assessment

## Overview
This project involves conducting a vulnerability assessment of my home network using Nmap, aimed at identifying potential security vulnerabilities and understanding the devices connected to the network.

## Objectives
- Assess the security of my home network.
- Identify open ports and services running on connected devices.
- Document findings and suggest remediation strategies.

## Tools Used
- **Nmap:** Network scanning tool
- **Wireshark:** (optional) For packet analysis

## Steps Taken
1. **Preparation**
   - Installed Nmap and reviewed basic commands.

2. **Network Scanning**
   - Conducted scans to identify devices and services:
     - Basic scan: `nmap -sn 192.168.100.0/24`
     - Open ports: `nmap -sS 192.168.100.21`
     - Version detection: `nmap -sV 192.168.100.21`

3. **Analysis of Results**
   - Documented findings in `scan_results.md`.

4. **Remediation Recommendations**
   - Suggested steps in `remediation_steps.md`.

## Future Improvements
- Implement regular scans.
- Explore additional vulnerability assessment tools.
diation_steps.md


remediation_steps.md
# Remediation Steps

1. **Close Unnecessary Ports**
   - Disable any services not in use (e.g., disable SSH if not needed).

2. **Update Software**
   - Ensure that all software is up to date to mitigate known vulnerabilities.

3. **Enable Firewall**
   - Implement firewall rules to restrict access to sensitive ports.
     
 Include Nmap Output
 nmap -sS 192.168.100.21 > nmap_output.txt
