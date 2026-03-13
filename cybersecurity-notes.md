# CYBERSECURITY BASICS - QUICK REFERENCE

## 🔐 CIA TRIAD
| Principle | Meaning | Example |
|-----------|---------|---------|
| **Confidentiality** | Only authorized users access data | Encryption, Passwords |
| **Integrity** | Data is accurate & unmodified | Hashing, Checksums |
| **Availability** | Data accessible when needed | Backups, Redundancy |

## 🚨 COMMON THREATS
| Threat | Description | Example |
|--------|-------------|---------|
| **Phishing** | Fake emails/messages to steal info | "Your bank account locked" email |
| **Malware** | Malicious software | Viruses, Worms, Trojans |
| **Ransomware** | Encrypts files, demands payment | WannaCry attack |
| **DDoS** | Flood system with traffic | Website crashes |
| **SQL Injection** | Malicious SQL in database queries | Login bypass: `' OR '1'='1` |
| **Brute Force** | Try all password combinations | Hydra, John the Ripper |

## 🎯 ATTACK VECTORS
- **Social Engineering:** Manipulating people (pretexting, baiting, tailgating)
- **Wireless Attacks:** Evil Twin, Packet Sniffing, Deauth attacks
- **Insider Threats:** Malicious, accidental, or compromised employees

## 🌐 OSI MODEL (7 Layers)
| Layer | Name | Examples |
|-------|------|----------|
| 7 | Application | HTTP, FTP, DNS |
| 6 | Presentation | Encryption, SSL |
| 5 | Session | Session management |
| 4 | Transport | TCP, UDP |
| 3 | Network | IP, ICMP |
| 2 | Data Link | MAC addresses, Switches |
| 1 | Physical | Cables, Hubs |

**Mnemonic:** "Please Do Not Throw Sausage Pizza Away"

## 🔌 IMPORTANT PORTS
| Port | Service |
|------|---------|
| 20,21 | FTP |
| 22 | SSH |
| 23 | Telnet |
| 25 | SMTP |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 445 | SMB |
| 3306 | MySQL |
| 3389 | RDP |

## 🔑 CRYPTOGRAPHY BASICS
- **Symmetric:** Same key encrypt/decrypt (AES)
- **Asymmetric:** Public/private keys (RSA)
- **Hashing:** One-way, can't reverse (SHA256)

## 🛠️ COMMON TOOLS
| Tool | Purpose |
|------|---------|
| Wireshark | Packet capture |
| Nmap | Network scanning |
| Burp Suite | Web app testing |
| Metasploit | Penetration testing |
| John/Hydra | Password attacks |