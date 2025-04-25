# OWASP Top 10: Cryptographic Failures

## 🕵️ Overview

This project involves identifying cryptographic failures in a vulnerable web application. The lab demonstrates how poor encryption practices and improper handling of API responses can expose sensitive user data.

---

## 🛠️ Tools & Techniques Used

- **Chrome Developer Tools**: Identified sensitive data exposed through unencrypted API responses.
- **Burp Suite**: Intercepted and analyzed web traffic to detect vulnerabilities.
- **JSON Response Analysis**: Identified poor object structure leading to data exposure.

---

## 🧪 Procedure

1. **Log in and Inspect User Data**: Used Chrome’s DevTools to inspect the application and view exposed user information.
2. **Examine API Responses**: Found sensitive data, such as email addresses and password hashes, being returned via a weak API.
3. **Review Data Structure**: Discovered recursive JSON objects causing sensitive data exposure.

---

## 🧠 Lessons Learned

- Proper object structuring is critical to prevent data exposure.
- APIs must ensure that only necessary data is returned and encrypted.
- Sensitive data should never be exposed in clear text, even if hashed.

---

## 📄 Full Lab Report (PDF)

For a comprehensive analysis of the cryptographic failures found in the lab, please download the full report.

[OWASP PDF.pdf](https://github.com/user-attachments/files/19912506/OWASP.PDF.pdf)

