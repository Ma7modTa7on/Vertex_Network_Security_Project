# Nmap Network Scanning 🔎

## 📌 What is Nmap Scanning?

Nmap scanning is a network reconnaissance technique used to discover active hosts, open ports, running services, and potentially vulnerable systems within a network.

Attackers can use network scanning during the reconnaissance phase to understand the structure of a target network and identify possible entry points.

* * *

## ⚠️ Why is it Dangerous?

- Network Reconnaissance: Attackers can discover active systems and network devices.
- Port Discovery: Open ports can reveal exposed services.
- Service Enumeration: Service versions can help attackers identify vulnerable software.
- Attack Planning: Information gathered during scanning can be used to prepare further attacks.

* * *

## 🧪 Attack Demonstration (Before Rules)

In the `Before_Rules` phase, network scanning is performed without sufficient security controls.

The attacker scans the network to identify reachable hosts, open ports, and exposed services.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/Nmap/Before_Rules

* * *

## 🛡️ Defense Demonstration (After Rules)

In the `After_Rules` phase, network security rules are applied to reduce unnecessary exposure and restrict unauthorized scanning activity.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/Nmap/After_Rules

* * *

## 🛡️ Defense Mechanisms

1. **Firewall Rules**
   - Restrict unnecessary inbound and outbound traffic.

2. **Network Segmentation**
   - Separate critical systems into isolated network segments.

3. **IDS/IPS**
   - Detect and alert on suspicious scanning and reconnaissance activity.

4. **Port Hardening**
   - Close unnecessary ports and disable unused services.

5. **Log Monitoring**
   - Monitor repeated connection attempts and unusual scanning patterns.

* * *

## 📚 Key Takeaways

- Network scanning is commonly used during the reconnaissance phase of an attack.
- Open ports and exposed services increase the attack surface.
- Proper firewall configuration can reduce network exposure.
- Continuous monitoring helps detect reconnaissance activity early.

* * *

## 👨‍💻 Author

- Mahmoud Ta7on
- salma ghareeb
- waad wael 
- Cybersecurity & Network Security Enthusiast

