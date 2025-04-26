# 🧪 Lab 03: SQL Injection - Filter Bypass via XML Encoding

---

## 🧠 Lab Overview
In this lab, the goal was to bypass a filter applied to an input field that blocks certain SQL injection payloads. The lab focused on using XML encoding techniques to evade the filter and execute a successful SQL injection.

---

## ⚙️ Steps Followed

1. Analyzed the input fields and identified the filter blocking common SQL injection payloads.
2. Attempted various encoding techniques, focusing on XML encoding.
3. Successfully bypassed the filter by using XML encoding to manipulate the SQL query.

---

## 🔥 Payloads Used

- `' OR 1=1--`
- `'; UNION SELECT NULL, username, password FROM users--`
- `<!--' OR 1=1-->`

---

## 🧠 Key Learnings

- XML encoding can be a useful technique to bypass simple input filters.
- Always ensure input sanitization does not just block simple payloads but accounts for encoding-based evasion techniques.
- It's important to test different encoding formats when dealing with web applications using filters to prevent SQL injection.

---

## 🛡️ Mitigation Techniques

- Use robust input validation and sanitization, ensuring filters do not just block specific characters but also account for different encoding techniques.
- Implement prepared statements and parameterized queries to prevent SQL injection vulnerabilities.
- Apply Web Application Firewalls (WAFs) to detect and block encoded payloads.

---

## 📚 References

- [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)
- [PortSwigger Academy - SQLi Filter Bypass](https://portswigger.net/web-security/sql-injection)

---
