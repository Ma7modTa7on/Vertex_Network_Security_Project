# Vertex_Network_Security_Project
Segment Enterprise Network Security Lab


A practical Enterprise Network Security Lab designed to simulate common cyber attacks, analyze their impact, and implement defensive security controls using network segmentation, firewall rules, and OPNsense.

 Project Overview

This project simulates a segmented enterprise network containing different security zones such as:

🌐 WAN
🛡️ DMZ
🔐 LAN

The main goal is to demonstrate how attackers can exploit network and application weaknesses and how defensive security controls can be used to detect, block, and reduce the impact of these attacks.

⚔️ Attacks Covered

The project demonstrates the following security scenarios:

Attack	Description	Main Defense
🔑 Brute Force	Repeated login attempts to gain unauthorized access	Rate Limiting, Account Lockout, MFA
🌐 DMZ → LAN	Attempt to move from a compromised DMZ system into the internal network	Firewall Rules & Network Segmentation
🚨 DoS / DDoS	Overloading a service to make it unavailable	Traffic Filtering & Rate Limiting
🕵️ MITM / ARP Spoofing	Intercepting traffic between network devices	ARP Protection & Network Segmentation
🔍 Nmap Reconnaissance	Discovering hosts, ports, and exposed services	Firewall & Service Restriction
💉 SQL Injection	Exploiting insecure database queries	Prepared Statements & Input Validation
🌐 XSS	Injecting malicious scripts into web applications	Output Encoding & CSP
🏗️ Network Architecture
                         INTERNET
                            |
                            |
                       ┌───────────┐
                       │ OPNsense  │
                       │ Firewall  │
                       └─────┬─────┘
                             |
              ┌──────────────┴──────────────┐
              |                             |
             DMZ                           LAN
              |                             |
        ┌───────────┐                ┌───────────┐
        │ Web/App   │                │ Internal  │
        │ Servers   │                │ Systems   │
        └───────────┘                └───────────┘

🔐 Security Concept

The network follows the principle of:

"Assume Breach + Defense in Depth"

A compromised machine should not automatically provide access to the rest of the network.

🛡️ Defense Strategy

The project uses multiple security layers:

                    SECURITY
                       |
        ┌──────────────┼──────────────┐
        |              |              |
     Firewall      Segmentation    Authentication
        |              |              |
        └──────────────┼──────────────┘
                       |
                  Monitoring
                       |
                    Logging
                       |
                   Detection
                       |
                   Response

Main Defensive Controls
🔥 Firewall Rules
🧱 Network Segmentation
🔐 Access Control
🔑 Strong Authentication
🚦 Rate Limiting
🕵️ Network Monitoring
📋 Logging
🛡️ Least Privilege
🔎 IDS/IPS concepts
🔥 OPNsense

OPNsense is used as the main firewall/security component of the lab.

It is responsible for controlling traffic between the different network zones.

Example Security Policy
WAN  → LAN   ❌ DENY
WAN  → DMZ   ✅ Allow Required Services
DMZ  → LAN   ❌ DENY
LAN  → DMZ   ✅ Allow Required Services
LAN  → WAN   ✅ According to Policy


This helps prevent lateral movement and limits the impact of a compromised system.

🧪 Testing Methodology

Each attack follows a simple security testing process:

        ┌───────────────┐
        │ Initial State │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Attack/Test   │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Observe Impact│
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Apply Defense │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Repeat Test   │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Compare Result│
        └───────────────┘


The project therefore focuses on both:

Offensive Security 🔴 + Defensive Security 🔵

📂 Project Structure
Vertex_Network_Security_Project/
│
├── Attacks/
│   │
│   ├── Brute_Force/
│   │
│   ├── DMZ_to_LAN/
│   │
│   ├── DOS-DDOS/
│   │
│   ├── MITM_Arp_Spoofing/
│   │
│   ├── Nmap/
│   │
│   └── SQLi-XSS/
│
└── README.md

🧰 Tools & Technologies
🛡️ OPNsense
🐧 Linux
🔍 Nmap
🦈 Wireshark
🌐 Web Security Testing Tools
🖥️ Virtual Machines
🔥 Firewall & ACL Rules
🧱 Network Segmentation / VLANs
📊 Security Objectives

The project aims to demonstrate how to:

Identify network vulnerabilities.
Perform controlled security testing.
Understand common attack techniques.
Analyze network traffic.
Configure firewall rules.
Isolate critical systems.
Prevent unauthorized access.
Reduce lateral movement.
Detect suspicious activity.
Compare network security before and after applying defenses.
🎓 Learning Outcomes

By completing this project, you gain practical experience in:

Network Security • Cybersecurity • Ethical Hacking • Firewall Configuration • OPNsense • Network Segmentation • Reconnaissance • Web Security • Traffic Analysis • Attack Detection • Defensive Security

🔴 Offensive Security

The offensive side of the project demonstrates how an attacker may:

Reconnaissance
      ↓
Identify Services
      ↓
Find Vulnerabilities
      ↓
Attempt Exploitation
      ↓
Analyze Impact

🔵 Defensive Security

The defensive side demonstrates how a security team can:

Identify Threat
      ↓
Apply Security Rules
      ↓
Block Unauthorized Traffic
      ↓
Monitor Network
      ↓
Analyze Logs
      ↓
Improve Security

📈 Final Result

The main objective is to show the difference between an unprotected network and a properly segmented and controlled network.

BEFORE
Attacker
   ↓
Vulnerable System
   ↓
Network Access
   ↓
Potential Lateral Movement

AFTER
Attacker
   ↓
Security Controls
   ↓
Firewall / Segmentation
   ↓
BLOCK / DETECT / LOG
   ↓
Reduced Impact

⚠️ Ethical Use

This project is intended for educational and authorized security testing only.

All attacks should be performed inside a controlled laboratory environment or against systems for which you have explicit authorization.

👨‍💻 Author

**Ma7modTa7on**
**salma ghareeb**
**waad wael**

⭐ Vertex Network Security Project

Learn the attack → Understand the vulnerability → Build the defense → Secure the network.
:::{"fallbackMarkdown":"","reference":{"matched_text":" ","prefix":null,"start_idx":7349,"end_idx":7349,"safe_urls":[],"refs":[],"alt":"","prompt_text":null,"type":"sources_footnote","sources":[{"title":"GitHub - Ma7modTa7on/Vertex_Network_Security_Project: Segment Enterprise Network Security Lab · GitHub","url":"https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main","attribution":"GitHub"}],"has_images":false},"showLoginRequiredCard":false}
