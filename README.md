# Nmap-network-scanning

##  Project Overview
This project demonstrates the use of **Nmap** to perform basic network reconnaissance by identifying active hosts, port states, and service exposure in a **safe and controlled environment**.

The scans were performed on the **local system and local network IPs** to understand how firewalls and network configurations affect scan results.

---

## Objective
- To understand how Nmap performs port scanning
- To analyze port states such as open, closed, and filtered
- To observe the impact of firewall protection on scan results
- To gain hands-on experience with basic network reconnaissance

---

##  Tools & Environment
- **Nmap**
- **Kali Linux**
- Local Wi-Fi network (authorized)
- Target IPs: `localhost`, `192.168.1.6` (own device)

---

##  Methodology

## Basic Port Scan
```bash
1️) nmap 192.168.1.6
Checked the default 1000 TCP ports

Verified host availability

2️) Fast Scan
nmap -F 192.168.1.6
Scanned common ports only

Used for quick reconnaissance

3️) Service & Version Detection
sudo nmap -sV 192.168.1.6
Attempted to identify running services and versions

4️) Localhost Scan
nmap localhost
sudo nmap -sV localhost
Used loopback interface to safely observe service detection

Avoided network firewall restrictions

## Observations & Results
The target host was reachable and online

All scanned ports on the local network IP were filtered

Filtered ports indicate firewall protection and no exposed services

Localhost scan demonstrated how services can be detected in a controlled environment

## Security Insight
Filtered ports reduce the attack surface and indicate a secure-by-default configuration, which is a recommended security practice in real-world environments.

## Key Learnings
Understanding how Nmap identifies host availability

Difference between open, closed, and filtered ports

Impact of firewalls on network scanning

Importance of scanning only authorized systems

Proper documentation of security findings

## Ethical Considerations
All scans were performed on authorized systems only (own machine and local environment).
No unauthorized or external targets were scanned.

## Screenshots
Screenshots of scan results are included in the screenshots/ directory for reference and documentation.

## Conclusion
This project provided hands-on experience with network scanning using Nmap and reinforced the importance of secure configurations and ethical security practices.

## Author
Anmol Bhonsle
