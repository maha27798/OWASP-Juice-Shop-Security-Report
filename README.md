# 🛡️ OWASP Juice Shop Security Assessment

This repository contains the complete documentation, evidence, and scan results from a web application security assessment conducted on the **OWASP Juice Shop**.  
It was performed as part of the **Cybersecurity Internship Program (Week 1)** to demonstrate practical vulnerability analysis, OWASP ZAP usage, and structured technical reporting.

---

## 👩‍💻 Author Information

| Field | Details |
|-------|---------|
| **Name** | Maha Fatima |
| **Intern ID** | DHC-345 |
| **Project Duration** | Week 1 – November 2025 |
| **Tools Used** | OWASP ZAP, Juice Shop, Browser DevTools, CTF CLI |

---

## 🎯 Objective

To perform a controlled, local security assessment of OWASP Juice Shop using both **manual testing** and **automated scanning**.  
The focus was on discovering vulnerabilities, capturing technical evidence, and producing a **professional security report**.

---

## 🧪 Scope of Work

- Setup & configuration of OWASP Juice Shop locally  
- Reconnaissance using **ZAP Spider** & **AJAX Spider**  
- Automated vulnerability scanning & evidence collection  
- Manual testing for:
  - XSS  
  - SQLi  
  - Input validation flaws  
- Structured documentation & indexing of all findings  

---

## 📊 Summary of Findings

| Vulnerability | Severity | Description |
|--------------|----------|-------------|
| **Sensitive Info Exposure** | 🔴 High | Dashboard displays user data without access control |
| **Info Disclosure** | 🟠 Medium | Session token exposed in URL (identified via ZAP scan) |
| **Error Handling Issue** | 🟢 Low | Improper rendering of JavaScript object (`[object Object]`) |

---

## ⚙️ Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|---------|
| **OWASP ZAP v2.11.1** | Automated scanning, spidering, alert generation |
| **Juice Shop (Localhost)** | Vulnerable testing application |
| **CTF CLI / Browser DevTools** | Manual payload execution & validation |
| **Markdown Reports** | Professional documentation |

---

