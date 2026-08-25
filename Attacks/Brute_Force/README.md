# Brute Force Attack 🔑

## 📌 What is Brute Force?
Brute Force is a **systematic attack technique** where an attacker attempts to guess valid login credentials by trying all possible combinations of usernames and passwords until successful access is achieved.

---

## ⚠️ Why is it Dangerous?
- **Unauthorized Access:** Attackers can gain entry into accounts or systems.
- **Data Breach:** Sensitive information may be exposed or stolen.
- **Privilege Escalation:** Compromised accounts can be used to gain higher-level access.
- **Service Disruption:** Continuous login attempts can overload authentication systems.

---

## 🧪 Attack Demonstration (Before Rules)
In the `before_rules` phase, the attacker repeatedly attempts logins using automated tools.  
📷 **Screenshot:**  
![Brute Force Screenshot](../../before_rules/brute_force.png)

---

## 🛡️ Defense Demonstration (After Rules)
In the `after_rules` phase, security measures are applied to stop the attack.  
📷 **Screenshot:**  
![Defense Screenshot](../../after_rules/brute_force_defense.png)

---

## 🛡️ Defense Mechanisms
To mitigate Brute Force attacks, the following security measures are applied:

1. **Strong Password Policies**  
   - Minimum length, complexity requirements, and regular rotation.
2. **Account Lockout Policies**  
   - Temporary or permanent lock after multiple failed attempts.
3. **Multi-Factor Authentication (MFA)**  
   - Adds an extra layer of security beyond passwords.
4. **Rate Limiting & Captcha**  
   - Prevents automated login attempts.
5. **Log Monitoring & Alerts**  
   - Detects suspicious login activity in real-time.

---

## 📚 Key Takeaways
- Brute Force is simple but effective against weak security setups.
- Defense requires a **layered approach** combining technical controls and user awareness.
- Always enforce **MFA** and **strong password policies** in enterprise environments.

---

## 👨‍💻 Author
- **Mahmoud Ta7on**  
- Cybersecurity & Network Security Enthusiast
