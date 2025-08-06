 🔐 Live Website Bug Reports – 

I manually tested over 20 live websites and found 11 different types of security vulnerabilities. This repository documents the vulnerabilities identified during testing.

---

## 📌 Summary

- Websites Tested:20+
- Vulnerabilities Found:11
-Testing Method: Manual, Black-box
- PoC: Not included
- Purpose:Educational / Ethical reporting

---

## 🐞 List of Vulnerabilities

| #  | Vulnerability             | Type           | Severity | Description |
|----|---------------------------|----------------|----------|-------------|
| 1  | HTML Injection            | Client-Side    | Medium   | Web page renders raw HTML from user input. |
| 2  | CSRF                      | Session/Auth   | High     | Requests can be forged without user consent. |
| 3  | XSS                       | Client-Side    | High     | Allows script injection into the browser. |
| 4  | Clickjacking              | UI/UX Abuse    | Medium   | Site can be embedded in an iframe without protection. |
| 5  | SQL Injection             | Server-Side    | Critical | User input directly affects SQL queries. |
| 6  | CORS Misconfiguration     | Access Control | High     | Cross-origin requests accepted from untrusted sources. |
| 7  | Buffer Overflow           | Memory Exploit | Critical | Unchecked input length may crash app or allow code execution. |
| 8  | OTP Bypass                | Authentication | High     | Insecure logic lets attacker skip OTP validation. |
| 9  | Insecure File Upload      | File Handling  | High     | No file type/content restrictions during upload. |
| 10 | Open URL Redirection      | Navigation     | Medium   | Redirects to external links without validation. |
| 11 | Path Traversal            | File Access    | Critical | Access to sensitive server files via ../ pattern. |

---

## ⚠️ Important Notes

- This repository contains no exploit code or proof-of-concept
- The findings are documented purely for educational purposes
- No unauthorized access or harm was caused
- Responsible disclosure is encouraged wherever applicable

---

## 👤 Author

Anjali Jain 
Email: anjalinolakha@gmail.com

---
