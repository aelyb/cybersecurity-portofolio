# CyberCourse – Secure Code Audit

This project presents a static code analysis of "CyberCourse," a peer-developed e-learning platform with student and tutor roles. The audit was conducted as part of a final project for Secure Programming, aimed at identifying critical vulnerabilities and providing secure coding recommendations.

### 🔍 Scope of Audit
- Cookie Tampering
- Insecure Direct Object Reference (IDOR)
- Cross-Site Scripting (XSS)
- CSRF Token Absence
- SQL Injection
- Weak Password Hashing (SHA1)
- Unsafe File Upload

### ✅ Key Findings
A total of **32 vulnerabilities** were found across various files. The issues included improper input handling, insecure cookie settings, lack of CSRF protection, outdated password hashing mechanisms, and unsafe file upload logic. Each issue was assessed using **CVSS v3.1**, and detailed code-level remediation was provided.

The application was found to be highly vulnerable across most core functions, and the report includes severity ratings, exploit explanations, and secure code recommendations for all identified issues.

📄 See the PDF file for the full vulnerability breakdown and code audit details.
