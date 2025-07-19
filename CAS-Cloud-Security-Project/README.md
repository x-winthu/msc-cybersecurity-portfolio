# ☁️ CAS – Cloud Architecture and Security Project

This project is part of the MSc Cybersecurity module *Cloud Architecture and Security (CAS)* at the National College of Ireland. It involves deploying and securing a WordPress-based web application on AWS.

## 🔧 Setup Overview
- Deployed on Amazon EC2 using LAMP stack (Linux, Apache, MySQL, PHP)
- Configured SSL/TLS with self-signed certificate
- Enforced security hardening steps via Apache and OS configuration

## 🧪 Security Testing Tools
- **Nmap** – Port scanning and service enumeration
- **WPScan** – WordPress vulnerability scanning
- **Nikto** – Web server vulnerability scan
- **Nessus** – Full vulnerability assessment
- **Firewall & Fail2Ban** – Protection and brute-force defense

## 🔐 Vulnerabilities Mitigated
- Disabled SSLv3; enforced TLS 1.2+
- Applied firewalld and MySQL binding rules
- Installed security headers (CSP, HSTS, X-Frame-Options)
- Patched CVEs on plugins and OS
- Implemented MFA for WordPress admin

## 📄 Report
Download full project report [here](./Cloud_Architecture_and_Security_Report.pdf)

---

> This work was submitted for the CAS module in MSc Cybersecurity (NCI, 2025).
