nmap-router-scan.md
Nmap Network Scan on Home Router
Tools Used:
- Nmap 7.97
- Windows Command Prompt
Objective:
Perform a basic port scan on my home router (Huawei) to identify open and filtered ports.
Command Used:nmap -T4 -F -v 192.168.18.1
Scan Output: PORT STATE SERVICE - 21/tcp filtered ftp, 22/tcp filtered ssh, 23/tcp filtered telnet, 53/tcp open domain, 80/tcp open http
Analysis:
- Port 53 (DNS) and Port 80 (HTTP) are open. This suggests the router is providing local name resolution and a web interface.
- Ports 21, 22, 23 are filtered, indicating firewall protection or disabled services.
- MAC address revealed the manufacturer: Huawei Technologies.
Lessons Learned:
- Gained hands-on experience using Nmap.
- Learned to interpret port states (open, filtered).
- Identified key services running on local network devices.
![Screenshot of Nmap scan]images/nmap-router-scan.png
