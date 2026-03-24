# Network Fundamentals – TryHackMe

Platform: TryHackMe   
Date Started: 31.01.2026  
Level:  Beginner / Foundation  
Focus Area: Networking for Cybersecurity  

## Objective

Build a strong foundation in networking concepts required for cybersecurity, including:  
- How devices communicate over networks  
- How data moves between systems  
- Core protocols and services  
- Network structures and security relevance  

## Core Concepts Learned  
### IP Addressing  
- **IPv4 / IPv6**  
- Public vs private IP addresses  
- Static vs dynamic IPs  
- Role of IP in routing and identification  

### Ports & Services  
- Ports as communication endpoints  
- Common ports:  
    - 80 → HTTP  
    - 443 → HTTPS  
    - 22 → SSH  
    - 21 → FTP  
- Services running on ports define system exposure  

### Protocols  
- TCP – reliable, connection-based communication  
- UDP – fast, connectionless communication  
- HTTP/HTTPS – web communication  
- DNS – domain name resolution  
- ICMP – diagnostics and network testing  

### Network Devices  
- Router – routes traffic between networks  
- Switch – connects devices within a network  
- Firewall – filters traffic based on rules  
- IDS/IPS – detects and blocks malicious traffic  

### Network Models  

- **OSI Model**  
Physical → Data Link → Network → Transport → Session → Presentation → Application  

- **TCP/IP Model**  
Network Interface → Internet → Transport → Application   

### VPN (Virtual Private Networks)  
- Secure encrypted communication over public networks  
- Used for privacy, remote access, and secure network connections  
 
Common VPN Technologies:  
PPTP – legacy VPN protocol (weak security)  
IPSec – secure VPN standard (strong encryption)  

## Practical Skills Developed   

1. Understanding traffic flow between systems  
2. Reading basic network diagrams  
3. Recognizing normal vs abnormal traffic behavior  
4. Identifying attack surfaces in network design  
5. Understanding how attacks move across networks  

## Tools Used  

- TryHackMe platform 
- Browser developer tools  
- Command-line tools:  
    - ping  
    - ipconfig / ifconfig  
    - tracert / traceroute  
    - nslookup  
    - netstat  

## Security Relevance  
 
Networking knowledge is critical for:  

- SOC monitoring and alert analysis  
- Incident response and investigation  
- Intrusion detection  
- Threat hunting  
- Network segmentation and defense  
- Understanding attack paths and lateral movement  

## Lessons Learned  

- Every cyber attack moves through a network  
- Logs and alerts are meaningless without network context  
- Network visibility = security visibility  
- Strong network fundamentals increase effectiveness in any cybersecurity role  