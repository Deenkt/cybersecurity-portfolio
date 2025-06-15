Project 2: Nmap Full Port Scan on Localhost (127.0.0.1)
Objective: To perform a full TCP port scan and service version detection on my own laptop (localhost)
Scan details: 127.0.0.1 (Local host)
Command used: nmap -sV -p- 127.0.0.1
View screenshot:![localhost_scan](Screenshot%202025-06-15%20074401.png)

Result summary: Host is up
Open Ports & Services Detected:
135/tcp – Microsoft Windows RPC
139/tcp – netbios-ssn (filtered)
445/tcp – Microsoft-DS (SMB file sharing)
902/tcp – VMware Authentication Daemon 1.10
912/tcp – VMware Authentication Daemon 1.0
5359/tcp – Unknown
5678/tcp – Unknown
49664-49672/tcp – Microsoft Windows RPC (multiple ephemeral ports)
What I Learned:
How to safely perform a full port scan on my own system
Recognized standard Windows services and their typical ports (RPC, SMB)
Discovered VMware services running locally — indicating virtualization tools
Learned to interpret filtered vs open port states
Tools Used:
Nmap version: 7.97 (on Windows)
System scanned: Windows 10 (Dell Optiplex)











