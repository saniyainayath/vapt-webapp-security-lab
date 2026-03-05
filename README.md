# vapt-webapp-security-lab
End-to-End Web Application Vulnerability Assessment &amp; Penetration Testing Lab
# Web Application VAPT Lab

This project demonstrates an **end-to-end Vulnerability Assessment and Penetration Testing (VAPT) lab** designed to simulate real-world web application and API security testing.

The lab environment was built using intentionally vulnerable applications and security tools to practice identifying, exploiting, and documenting security vulnerabilities.

---

## Lab Objectives

- Simulate real-world **web application penetration testing**
- Practice **OWASP Top 10 vulnerability exploitation**
- Understand **attack and detection techniques**
- Produce a **professional penetration testing report**

---

## Lab Environment

The testing environment included the following vulnerable applications:

- **DVWA (Damn Vulnerable Web Application)**
- **OWASP Juice Shop**
- **VAmPI (Vulnerable API)**

These applications were deployed in a **Docker-based lab environment** to simulate realistic attack scenarios.

---

## Tools Used

- Burp Suite
- sqlmap
- ffuf
- Nmap
- ELK Stack
- Docker

---

## Vulnerabilities Exploited

The lab covered multiple real-world vulnerability scenarios including:

- SQL Injection
- Stored Cross-Site Scripting (XSS)
- Reflected Cross-Site Scripting
- Insecure Direct Object Reference (IDOR)
- JWT `alg:none` Authentication Bypass
- Mass Assignment vulnerabilities

---

## Detection Engineering

In addition to offensive testing, **ELK Stack detection rules** were implemented to identify malicious activity such as:

- SQL Injection payload patterns
- XSS attack attempts
- Vulnerability scanning activity
- Brute-force login attempts

This helped simulate how **Security Operations Centers detect attacks**.

---

## Penetration Testing Report

A complete professional **VAPT report** was created including:

- Vulnerability descriptions
- Risk severity assessment
- Proof-of-concept exploitation
- Remediation recommendations

📄 **Download the Report:**  
[VAPT Penetration Testing Report](./VAPT_Report_Web_App_Lab.pdf)

---

## Key Learning Outcomes

- Conducting structured **web application penetration testing**
- Identifying and exploiting **OWASP Top 10 vulnerabilities**
- Understanding **application security misconfigurations**
- Creating professional **security assessment reports**
- Integrating **offensive testing with defensive monitoring**

---

## Author

**Saniya Inayath**

Application Security | Penetration Testing | SOC Automation

LinkedIn: https://www.linkedin.com/in/saniyainayath/
Medium: https://medium.com/@saniyainayath

---
