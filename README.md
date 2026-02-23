# FUTURE_CS_01  
Cyber Security Internship Task 1  
Future Interns – Vulnerability Assessment Report  

---

## 📌 Project Overview

This repository contains the deliverables for Task 1 of the Future Interns Cyber Security Internship Program.

The objective of this task was to conduct a **read-only vulnerability assessment** of a public website and present findings in a professional audit report format.

---

## 🌐 Website Assessed

http://testphp.vulnweb.com

---

## 🔍 Scope & Methodology

This assessment was strictly limited to passive analysis, including:

- Port and service enumeration using Nmap
- Security header analysis using SecurityHeaders.com
- Manual browser inspection
- Header and configuration review using OWASP ZAP (Passive Only)

⚠️ No exploitation or active attack techniques were performed.

---

## 🛠 Tools Used

- Nmap 7.98
- SecurityHeaders.com
- OWASP ZAP (Passive Mode)
- Google Chrome DevTools

---

## 🚨 Summary of Findings

| ID | Finding | Risk Level |
|----|---------|------------|
| 1  | Website served over HTTP (No HTTPS) | High |
| 2  | Missing Content-Security-Policy | Medium |
| 3  | Missing X-Frame-Options | Medium |
| 4  | Server Version Disclosure (nginx 1.19.0) | Medium |
| 5  | X-Powered-By Header Disclosure | Medium |
| 6  | Missing X-Content-Type-Options | Low |
| 7  | Missing Referrer-Policy | Low |

---

## 📂 Repository Structure
