# 🧪 Lab 01: SQL Injection - Hidden Data Retrieval

---

## 🧠 Lab Overview
In this lab, the goal was to retrieve hidden data by exploiting a SQL injection vulnerability in the WHERE clause of a query.

---

## ⚙️ Steps Followed

1. Identified input fields vulnerable to SQL injection.
2. Crafted payloads to manipulate the WHERE clause.
3. Retrieved hidden product details by injecting `' OR 1=1--` payload.

---

## 🔥 Payloads Used

- `' OR 1=1--`
- `' UNION SELECT NULL, username, password FROM users--`

---

## 🧠 Key Learnings

- Basics of SQL injection in WHERE clauses.
- Importance of input validation and prepared statements.
- Impact of SQLi on data confidentiality.

---

## 🛡️ Mitigation Techniques

- Use parameterized queries (prepared statements).
- Input validation and sanitization.
- Proper error handling to avoid information disclosure.

---

## 📚 References

- [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)
- [PortSwigger Academy - SQLi](https://portswigger.net/web-security/sql-injection)

---
