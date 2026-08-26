# DMZ to LAN Attack 🔐

## 📌 What is a DMZ to LAN Attack?

A DMZ to LAN attack occurs when an attacker compromises a system located in the DMZ and then attempts to move from the DMZ into the internal LAN network.

The goal is usually to reach internal systems, services, or sensitive resources that should not be directly accessible from the DMZ.

* * *

## ⚠️ Why is it Dangerous?

- Lateral Movement: An attacker may move from a compromised DMZ system toward internal systems.
- Internal Network Exposure: Poorly configured firewall rules may expose LAN services.
- Data Access: Attackers may attempt to access sensitive internal resources.
- Network Compromise: Successful movement into the LAN can increase the impact of the initial compromise.

* * *

## 🧪 Attack Demonstration (Before Rules)

In the `Before_Rules` phase, insufficient network segmentation or firewall restrictions may allow traffic from the DMZ toward internal LAN resources.

The attacker attempts to communicate with or access services located inside the LAN.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/DMZ_to_LAN/Before_Rules

* * *

## 🛡️ Defense Demonstration (After Rules)

In the `After_Rules` phase, firewall rules are applied to restrict traffic originating from the DMZ toward the internal LAN.

Only explicitly required communication is allowed.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/DMZ_to_LAN/Ater_Rules

* * *

## 🛡️ Defense Mechanisms

1. **Network Segmentation**
   - Keep DMZ and LAN networks separated.

2. **Firewall Rules**
   - Block unnecessary DMZ-to-LAN traffic.

3. **Least Privilege**
   - Allow only the specific services and ports required for legitimate communication.

4. **Access Control**
   - Restrict access to sensitive internal resources.

5. **Monitoring & Logging**
   - Monitor traffic between DMZ and LAN for suspicious activity.

* * *

## 📚 Key Takeaways

- The DMZ should be treated as a less-trusted network.
- Direct access from the DMZ to sensitive LAN resources should be minimized.
- Firewall rules are essential for controlling traffic between network zones.
- Network segmentation can limit lateral movement.
- Monitoring can help detect unauthorized attempts to access internal systems.

* * *

## 👨‍💻 Author

- **Mahmoud Ta7on**
- **salma ghareeb**
-**waad wael**
- Cybersecurity & Network Security Enthusiast

