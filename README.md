# Nmap-network-scanning

##  Project Overview

This project demonstrates the use of Nmap to perform basic network reconnaissance by identifying host availability, port states, and service exposure in a safe and controlled environment. The scans were conducted only on authorized systems to understand how firewall configurations affect scan results.

## Objective
The objective of this project is to learn how Nmap performs network scanning, identify open, closed, and filtered ports, and understand the importance of secure network configurations from a defensive security perspective.

## Tools and Environment
Tool used: Nmap
Operating System: Kali Linux
Network: Local Wi-Fi (authorized)
Target IPs: localhost and personal device IP (192.168.1.6)

## Methodology

## Step 1: Basic Port Scan
A basic Nmap scan was performed to check host availability and scan the default set of TCP ports.

## Step 2: Fast Scan
A fast scan was conducted to quickly analyze commonly used ports and understand quick reconnaissance techniques.

## Step 3: Service and Version Detection
Service detection was attempted to identify any running services and their versions on the target system.

## Step 4: Localhost Scan
A localhost scan was performed to safely demonstrate service detection without interference from external firewalls.

## Observations and Results
The target host was reachable and active.
All scanned ports on the local network IP were found to be filtered, indicating firewall protection.
No externally exposed services were detected on the local network interface.
Localhost scanning helped demonstrate how Nmap identifies services in a controlled environment.

## Security Insight
Filtered ports indicate a secure configuration where unnecessary services are not exposed. This reduces the attack surface and is considered a best practice in real-world security environments.

## Key Learnings
Understanding how Nmap performs network reconnaissance
Identifying different port states such as open, closed, and filtered
Learning how firewalls affect scan results
Gaining awareness of ethical and authorized scanning practices
Improving documentation and reporting skills

## Ethical Considerations
All scans were performed only on systems owned by the user or explicitly authorized for testing. No unauthorized or external targets were scanned during this project.

## Conclusion
This project provided hands-on experience with Nmap and reinforced the importance of secure configurations and ethical behavior in cybersecurity. It helped build a foundational understanding of network scanning techniques used in security operations.

## Author
Anmol Bhonsle
