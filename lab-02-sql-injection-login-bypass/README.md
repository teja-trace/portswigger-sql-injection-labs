# 🧪 Lab 02: SQL Injection - Login Bypass

---

## 🧠 Lab Overview
In this lab, the goal was to bypass the login authentication mechanism of a web application by exploiting an SQL injection vulnerability in the login form.

---

## ⚙️ Steps Followed

1. Analyzed the login form input fields for SQL injection vulnerabilities.
2. Crafted payloads to manipulate the authentication query.
3. Successfully bypassed the login mechanism using the payload `' OR '1'='1`.

---

## 🔥 Payloads Used

- `' OR '1'='1`
- `' UNION SELECT NULL, username, password FROM users--`

---

## 🧠 Key Learnings

- SQL injection in login forms is one of the most common vulnerabilities.
- Importance of using secure authentication mechanisms like parameterized queries.

---

## 🛡️ Mitigation Techniques

- Use parameterized queries to prevent SQL injection.
- Implement proper authentication mechanisms (e.g., multi-factor authentication).
- Validate and sanitize user inputs.

---

## 📚 References

- [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)
- [PortSwigger Academy - SQLi](https://portswigger.net/web-security/sql-injection)

---
