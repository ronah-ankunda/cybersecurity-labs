Cybersecurity Labs

Hands-on security labs completed as part of my MSc in Cybersecurity at Hood College. Work spans digital forensics, penetration testing, network security, and security operations.

---

Digital Forensics

**Clampet Forensic Investigation**  
Full investigation using AccessData FTK on the Clampet18.aff disk image. Identified primary suspect through browser cache artifacts, recovered moonshine recipes, a password-protected customer spreadsheet, and internet search history corroborating witness statements.  
Tools: AccessData FTK, FTK Imager

**Registry and User Account Analysis**  
Exported SAM and SYSTEM registry files from the Washer.E01 image using FTK Imager. Analyzed user accounts and registry artifacts using Registry Viewer.  
Tools: FTK Imager, Registry Viewer

---

Penetration Testing

**Metasploitable2: SMB Exploitation**  
Enumerated SMB with enum4linux, identified Samba 3.0.20-Debian, exploited CVE-2007-2447 for a reverse shell. Cracked password hashes with John the Ripper.  
Tools: Metasploit, Nmap, enum4linux, John the Ripper

**DVWA: Web Application Command Injection**  
Exploited command injection in DVWA. Analyzed PHP source code and injected OS commands to enumerate system users.  
Tools: Burp Suite, Kali Linux

**Wireless Network Exploitation**  
Analyzed packet capture in Wireshark. Used aircrack-ng to crack wireless password.  
Tools: Wireshark, aircrack-ng, Kali Linux
