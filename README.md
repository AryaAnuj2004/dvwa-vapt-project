# Vulnerability Assessment and Penetration Testing (VAPT) on a Web Application

This repository contains a complete Vulnerability Assessment and Penetration Testing (VAPT) report based on testing the [Damn Vulnerable Web Application (DVWA)](http://www.dvwa.co.uk/) using Kali Linux.

---

## 📌 Project Overview

- **Target Application:** DVWA (Localhost:127.0.0.1)
- **Environment:** Kali Linux (Apache, PHP, MySQL, Burp Suite)
- **Purpose:** To identify and exploit common web application vulnerabilities in a controlled environment.

---

## 🔍 Vulnerabilities Tested

The following DVWA modules were tested with documented steps and screenshots:

| # | Vulnerability Type           | Status     |
|---|------------------------------|------------|
| 1 | Brute Force                  | ✅ Tested   |
| 2 | CSRF                         | ✅ Tested   |
| 3 | SQL Injection                | ✅ Tested   |
| 4 | SQL Injection (Blind)        | ✅ Tested   |
| 5 | XSS (DOM-Based)              | ✅ Tested   |
| 6 | XSS (Reflected)              | ✅ Tested   |
| 7 | XSS (Stored)                 | ✅ Tested   |
| 8 | CSP Bypass                   | ✅ Tested   |
| 9 | Authorization Bypass        | ✅ Tested   |
|10 | Open HTTP Redirect           | ✅ Tested   |
|11 | Cryptography Flaws           | ✅ Reviewed |
|12 | JavaScript/Client-side Bypass| ✅ Reviewed |
|13 | API Security (if enabled)    | ✅ Reviewed |

---

## 🛠 Tools Used

- 🐧 Kali Linux (2024)
- 🌐 DVWA (PHP/MySQL Web App)
- 🛡 Burp Suite Community Edition
- 🐍 Custom PoC scripts
- 🧠 Manual testing techniques

---

## 📁 Project Structure
```
dvwa-vapt-project/
│
├── README.md
├── DVWA_VAPT_Report.pdf
├── csrf-poc.html
├── screenshots/
│ ├── xss_stored_payload.png
│ ├── sqli_result.png
│ └── csrf_exploit_form.png
```


---

## 🧾 Report Contents

- Detailed vulnerability explanation
- Exploitation methodology
- Screenshots
- Impact analysis
- Mitigation recommendations

---

## 🛡 Disclaimer

> This project is conducted on **DVWA**, a deliberately vulnerable environment. All tests were performed in a legal and educational context. Never use these techniques on real systems without authorization.

---

## 📧 Contact

Feel free to reach out for collaboration or questions:

- **Name:** Anuj Kumar Arya
- **LinkedIn:** [Anuj Kr Arya](www.linkedin.com/in/anujkrarya)
- **Email:** [aryaanuj007@gmail.com](mailto:aryaanuj007@gmail.com)
- **GitHub:** [https://github.com/AryaAnuj2004](https://github.com/AryaAnuj2004)

---

