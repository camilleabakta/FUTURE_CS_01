# Future Interns - Cyber Security Internship
## Task 1: Web Application Security Testing

### 👤 Intern Information
- **Name:** ABAKTA Haana Camille
- **Assignment:** Task 1 - Vulnerability Assessment
- **Target Application:** OWASP Juice Shop
- **Date:** January 5, 2026

---

### 📝 Project Overview
The objective of this task was to perform a comprehensive vulnerability assessment of a web application to identify security flaws, evaluate their impact, and provide remediation steps.

This project involved setting up a controlled environment to simulate a real-world penetration testing scenario using professional tools and methodologies.

### 🛠️ Environment & Tools
- **Virtualization:** VMware Workstation Player
- **Operating System:** Kali Linux
- **Scanning Tool:** OWASP ZAP (Zed Attack Proxy) v2.17.0
- **Containerization:** Docker (to host OWASP Juice Shop)

### 🚀 Methodology
1. **Environment Setup:** Deployed OWASP Juice Shop via Docker on Kali Linux.
2. **Reconnaissance:** Used ZAP Spider to map the application's directory structure.
3. **Vulnerability Scanning:** Performed an automated DAST (Dynamic Application Security Testing) scan.
4. **Analysis:** Analyzed alerts and mapped them to the **OWASP Top 10 (2021)** framework.
5. **Reporting:** Documented findings, evidence (screenshots), and mitigation steps in a formal PDF report.

### 🔍 Key Findings
During the assessment, **15 security alerts** were identified, including:
- **High Severity:** SQL Injection (A03:2021 - Injection)
- **Medium Severity:** Vulnerable JS Libraries (A06:2021 - Vulnerable and Outdated Components)
- **Medium Severity:** Missing Security Headers (A05:2021 - Security Misconfiguration)

### 📁 Deliverables
- [X] **PDF Report:** Full detailed assessment with screenshots and remediation steps.
- [X] **Scan Report** The HTML report for the scan.

---
*Disclaimer: This project was conducted in a local, isolated environment for educational purposes as part of the Future Interns internship program.*
