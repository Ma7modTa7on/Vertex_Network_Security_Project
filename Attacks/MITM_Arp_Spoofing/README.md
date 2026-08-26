# MITM ARP Spoofing Attack 🕵️

## 📌 What is ARP Spoofing?

ARP Spoofing is a Man-in-the-Middle (MITM) attack technique where an attacker sends forged ARP messages to associate their MAC address with the IP address of another device, such as the network gateway.

This can allow the attacker to intercept or manipulate network traffic between two devices.

* * *

## ⚠️ Why is it Dangerous?

- Traffic Interception: Attackers may intercept network communications.
- Credential Exposure: Unencrypted credentials and sensitive information may be exposed.
- Traffic Manipulation: Network traffic can potentially be modified in transit.
- Network Disruption: Incorrect ARP mappings can interrupt communication between devices.

* * *

## 🧪 Attack Demonstration (Before Rules)

In the `Before_Rules` phase, ARP spoofing is performed against devices on the local network.

The attacker attempts to position themselves between the victim and the gateway to observe network traffic.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/MITM_Arp_Spoofing/Before_Rules

* * *

## 🛡️ Defense Demonstration (After Rules)

In the `After_Rules` phase, network security controls are applied to reduce the possibility of ARP spoofing and MITM attacks.

📷 Screenshot  https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/MITM_Arp_Spoofing/After_Rules

* * *

## 🛡️ Defense Mechanisms

1. **Dynamic ARP Inspection**
   - Validates ARP packets and blocks suspicious ARP activity.

2. **DHCP Snooping**
   - Helps establish trusted IP-to-MAC bindings.

3. **Network Segmentation**
   - Limits the scope of potential MITM attacks.

4. **Static ARP Entries**
   - Can be used for critical systems where appropriate.

5. **Encryption**
   - HTTPS, SSH, and VPN encryption helps protect data even if traffic is intercepted.

* * *

## 📚 Key Takeaways

- ARP Spoofing is a common technique used to perform local-network MITM attacks.
- Attackers can exploit the lack of ARP authentication.
- DHCP Snooping and Dynamic ARP Inspection can reduce the risk.
- Encryption provides an additional layer of protection for sensitive communications.

* * *

## 👨‍💻 Author

- Mahmoud Ta7on
- salma ghareeb
- waad wael
- Cybersecurity & Network Security Enthusiast

