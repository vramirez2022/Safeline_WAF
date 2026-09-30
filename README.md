# 🛡️ SafeLine WAF & Threat Mitigation Homelab

An enterprise-grade Web Application Firewall (WAF) deployment and threat mitigation lab. This project demonstrates an inline reverse proxy defense architecture using **SafeLine WAF** to protect an intentionally vulnerable web application (**OWASP Juice Shop**), validating real-time threat detection, automated payload blocking, and security telemetry logging.

---

## 🎯 Objectives & Key Takeaways

* **Inline Defense Architecture:** Deployed SafeLine WAF as a reverse proxy inspecting inbound HTTP/HTTPS traffic before reaching downstream services.
* **Attack Execution & Validation:** Tested real-world attack vectors against OWASP Top 10 vulnerabilities, including SQL Injection (SQLi), Cross-Site Scripting (XSS), and Path Traversal.
* **Automated Threat Mitigation:** Verified real-time rule engine execution, traffic dropping, and response interception (`403 Forbidden`).
* **Security Telemetry & Analysis:** Monitored alert telemetry, sanitized log outputs, and analyzed malicious payload signatures in the detection console.

---

## 🛠️ Tech Stack & Skills Highlighted

### **Cybersecurity & Threat Detection**
* **Web Application Firewall:** SafeLine WAF (Traffic filtering, IP rate-limiting, custom rule tuning)
* **Threat Mitigation:** Payload inspection, log analysis, alert sanitization, attack vector neutralization
* **Security Frameworks:** OWASP Top 10 Web Application Security Risks

### **Full-Stack & Infrastructure**
* **Target Application:** OWASP Juice Shop (Node.js, Express, SQLite REST API)
* **Networking & Web Architecture:** Reverse Proxy configuration, HTTP request routing, header analysis
* **Containerization:** Docker & Docker Compose

---

## 🏗️ Architecture Overview
