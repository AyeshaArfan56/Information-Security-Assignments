# Assignment 01 – Information Security (CS-460)

## 📝 Description
This assignment focuses on identifying vulnerabilities in a small company's information security setup and implementing a Python program to check password strength.

---

## 📌 Question 1: Security Vulnerability Assessment

As the Information Security Officer of a small company that has recently experienced a data breach, you are tasked with improving its security posture.

### 🔍 Task:
1. Identify **three potential vulnerabilities** in the current security setup.
2. Propose **mitigation measures** for each vulnerability.

---

## 💻 Question 2: Password Strength Checker

Write a Python function to check the strength of a given password. The password is considered strong if:

- It has **6 to 20 characters**.
- It contains **at least one lowercase letter**, **one uppercase letter**, and **one digit**.
- It **does not contain three repeating characters** in a row (e.g., `"aaa"` is invalid).

### ✅ Function Specification

```python
def is_strong_password(password: str) -> bool:
    ...
