# SQL Injection & XSS Attacks 💉

## 📌 What are SQL Injection & XSS?

SQL Injection (SQLi) is a web application attack where malicious input is used to manipulate SQL queries executed by the application.

Cross-Site Scripting (XSS) is a web security vulnerability where malicious scripts are injected into web pages and executed in a victim's browser.

Both attacks commonly occur when user input is not properly validated, sanitized, or safely handled.

* * *

## ⚠️ Why are they Dangerous?

- Data Exposure: SQL Injection can expose sensitive database information.
- Authentication Bypass: SQL Injection may allow attackers to bypass application authentication.
- Database Manipulation: Attackers may modify or delete database information.
- Script Execution: XSS can cause malicious JavaScript to execute in a victim's browser.
- Session Theft: XSS can potentially expose sensitive session information when applications are improperly protected.

* * *

## 🧪 Attack Demonstration (Before Rules)

In the `Before_Rules` phase, the web application is exposed without sufficient input validation and security controls.

The attacker sends malicious input to test whether the application is vulnerable to SQL Injection or Cross-Site Scripting.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/SQLi-XSS/Before_Rules

* * *

## 🛡️ Defense Demonstration (After Rules)

In the `After_Rules` phase, security rules and input protection mechanisms are applied to detect and block suspicious web requests.

📷 Screenshot https://github.com/Ma7modTa7on/Vertex_Network_Security_Project/tree/main/Attacks/SQLi-XSS/After_Rules

* * *

## 🛡️ Defense Mechanisms

1. **Input Validation**
   - Validate user input before processing it.

2. **Parameterized Queries**
   - Use prepared statements instead of dynamically constructing SQL queries.

3. **Output Encoding**
   - Encode user-controlled data before displaying it in web pages.

4. **Web Application Firewall (WAF)**
   - Detect and block suspicious web requests.

5. **Secure Application Development**
   - Follow secure coding practices and regularly test applications for vulnerabilities.

* * *

## 📚 Key Takeaways

- SQL Injection and XSS are common web application vulnerabilities.
- Improper input handling can expose applications to malicious input.
- Parameterized queries are an important defense against SQL Injection.
- Output encoding helps reduce the risk of XSS.
- WAF rules can provide an additional layer of protection.

* * *

## 👨‍💻 Author

- Mahmoud Ta7on
- salma ghareeb
- waad wael
- Cybersecurity & Network Security Enthusiast

