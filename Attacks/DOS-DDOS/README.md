# DoS / DDoS Attack 🌐

## 📌 What is DoS / DDoS?

A Denial-of-Service (DoS) attack attempts to make a system, application, or network service unavailable by overwhelming its resources.

A Distributed Denial-of-Service (DDoS) attack uses multiple sources to generate a large amount of traffic or requests toward the target.

* * *

## ⚠️ Why is it Dangerous?

- Service Disruption: Legitimate users may be unable to access services.
- Resource Exhaustion: CPU, memory, bandwidth, or connection resources may become overloaded.
- Availability Loss: Critical applications and services can become unavailable.
- Business Impact: Extended downtime can cause operational and financial losses.

* * *

## 🧪 Attack Demonstration (Before Rules)

In the `Before_Rules` phase, the target service is exposed without sufficient traffic filtering or rate-control mechanisms.

The attack generates excessive traffic or requests toward the target.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/DOS-DDOS/Before_Rules

* * *

## 🛡️ Defense Demonstration (After Rules)

In the `After_Rules` phase, defensive rules and traffic-control mechanisms are applied to limit abnormal traffic and protect service availability.

📷 Screenshot  https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/DOS-DDOS/After_Rules

* * *

## 🛡️ Defense Mechanisms

1. **Rate Limiting**
   - Limit the number of requests accepted from a source within a specific time period.

2. **Firewall Rules**
   - Filter suspicious and unwanted traffic.

3. **Traffic Monitoring**
   - Monitor bandwidth usage and unusual traffic spikes.

4. **Network Segmentation**
   - Isolate critical services from unnecessary network exposure.

5. **DDoS Protection**
   - Use appropriate upstream or cloud-based protection services when required.

* * *

## 📚 Key Takeaways

- DoS/DDoS attacks primarily target service availability.
- Traffic spikes and abnormal request patterns can indicate an attack.
- Rate limiting and traffic filtering can reduce the impact of many attacks.
- A layered defense strategy is important for maintaining service availability.

* * *

## 👨‍💻 Author

- **Mahmoud Ta7on**
- **salma ghareeb**
- **waad wael**
- Cybersecurity & Network Security Enthusiast

