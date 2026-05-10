Cybersecurity Labs
Hands-on security labs completed as part of my MSc in Cybersecurity at Hood College. Work spans digital forensics, penetration testing, network security, and security operations.
---
Digital Forensics
Clampet Forensic Investigation
Full investigation using AccessData FTK on the Clampet18.aff disk image. Identified primary suspect through browser cache artifacts, recovered moonshine recipes, a password-protected customer spreadsheet, and internet search history corroborating witness statements. Produced a structured forensic report with timestamped evidence.
Tools: AccessData FTK, FTK Imager
Registry and User Account Analysis
Exported SAM and SYSTEM registry files from the Washer.E01 image using FTK Imager. Analyzed user accounts and registry artifacts using AccessData Registry Viewer.
Tools: FTK Imager, Registry Viewer
Linux Filesystem and Inode Analysis
Loaded a Linux disk image (Ubuntu, Ext3) in FTK Imager and analyzed filesystem artifacts including inodes, directory structures, and file metadata.
Tools: FTK Imager
Hex Editor and Log Analysis
Examined raw file data at the byte level using a hex editor, analyzing file headers and identifying artifacts not visible at the application layer.
Tools: Hex Editor
---
Penetration Testing
Metasploitable2: SMB Exploitation
Used enum4linux for unauthenticated SMB enumeration, identified Samba 3.0.20-Debian via Metasploit auxiliary scanner, then exploited CVE-2007-2447 (usermap_script) to gain a reverse shell. Cracked password hashes using John the Ripper.
Tools: Metasploit, Nmap, enum4linux, John the Ripper
DVWA: Web Application Command Injection
Exploited command injection vulnerabilities in DVWA running on Metasploitable2. Analyzed PHP source code to identify unvalidated input, injected OS commands to enumerate system users.
Tools: Burp Suite, Kali Linux, DVWA
Wireless Network Exploitation
Analyzed a packet capture in Wireshark to identify target network, SSID, and a deauthentication flood attack. Used aircrack-ng to crack the wireless password.
Tools: Wireshark, aircrack-ng, Kali Linux
---
Network Security
ICMP Redirect Attack
Crafted spoofed ICMP redirect messages using Scapy to manipulate a victim's routing table and redirect traffic through a malicious gateway. Built on Docker-based lab environment.
Tools: Scapy, Docker, Wireshark
Heartbleed Vulnerability Analysis (CVE-2014-0160)
Analyzed the OpenSSL Heartbleed bug, tracing how unverified payload lengths in the memcpy() function allowed buffer over-reads of up to 64KB of server memory.
Network Traffic Analysis
Analyzed packet captures to identify web server, user agent, proxy configuration, and ports using HTTP and TCP filters in Wireshark.
Tools: Wireshark
Snort ICMP Lab
Configured Snort IDS rules to detect ICMP reconnaissance activity and validated detection against live packet captures.
Tools: Snort, Linux
GitHub: snort-icmp-lab
---
Security Operations
Intrusion Detection Systems
Analyzed statistical anomaly detection (threshold and profile-based) versus rule-based IDS approaches. Modeled detection metrics including counters, gauges, interval timers, and resource utilization.
IPsec and Network Security Protocols
Studied Authentication Header (AH) and Encapsulation Security Payload (ESP) protocols, IKE phase negotiation, transport vs. tunnel mode, and MAC calculation.
---
Tools Used
Splunk, QRadar, AccessData FTK, FTK Imager, Wireshark, Metasploit, Burp Suite, Nmap, Snort, aircrack-ng, Scapy, Kali Linux, John the Ripper, Docker
---
About
MSc Cybersecurity candidate at Hood College (GPA 3.77), graduating May 2026.
Portfolio: ronah-ankunda.github.io
LinkedIn: linkedin.com/in/ronah-ankunda
