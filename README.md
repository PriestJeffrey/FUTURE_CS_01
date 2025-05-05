# 🔐 DVWA Web Application Security Assessment

This repository contains a detailed penetration test report and artifacts for a web application security assessment project conducted on [Damn Vulnerable Web Application (DVWA)](https://dvwa.co.uk/). The project was carried out during my internship at **Future Interns** as part of my hands-on experience in offensive security and vulnerability analysis.

## 📌 Objective

The goal was to identify and exploit common web application vulnerabilities in DVWA, analyze risks, provide remediation steps, and gain real-world experience in ethical hacking and reporting.

## 🧠 What I Learned

- Manual and automated vulnerability testing
- Using tools like Burp Suite, SQLMap, and browser developer tools
- Writing professional penetration testing reports
- Hands-on with authentication flaws, XSS, and SQL injection
- Analyzing server-side behavior using session hijacking
- Creating structured documentation using Word and Excel

## 🛠 Tools & Tech Used

- 🔸 **Burp Suite** (Community Edition) – Interception & payload injection
- 🔸 **SQLMap** – Automated SQL injection tool
- 🔸 **DVWA (Dockerized)** – Testing platform
- 🔸 **curl & browser dev tools** – Manual request crafting
- 🔸 **Command Prompt & Git** – Project versioning
- 🔸 **Microsoft Word & Excel** – Reporting format

---

## 🐞 Vulnerabilities Tested

| Vulnerability       | Status     | Risk Level | Tools Used         |
|---------------------|------------|------------|---------------------|
| SQL Injection       | ✅ Found    | High       | SQLMap, Burp        |
| Reflected XSS       | ✅ Found    | Medium     | Manual, Burp        |
| Stored XSS          | ✅ Found    | High       | Manual              |
| Authentication Flaw | ✅ Found    | High       | Session hijacking   |

## This project was completed as part of my internship at Future Interns, with support and mentorship in real-world penetration testing methodology and reporting standards.

## ⚠️ Disclaimer
This project was conducted on a legal and intentionally vulnerable environment (DVWA) for educational purposes. 
Do not attempt these techniques on real-world systems without proper authorization.
