
````markdown
# 🔐 CS-460 Information Security – Assignment Repository

This repository contains all three assignments submitted for the **CS-460 Information Security** course. These assignments provide practical experience in core areas of information security such as vulnerability analysis, password policies, classical encryption techniques, and AES key expansion using Python.

---

## 📁 Assignment 1: Vulnerability Assessment & Password Strength Checker

### ✅ Task 1: Security Vulnerability Assessment (Theoretical)

As the Information Security Officer in a small company that recently suffered a data breach, the following actions were taken:

- **Identified three vulnerabilities** within the organization’s current security infrastructure.
- **Proposed effective mitigation strategies** to reduce risks associated with each vulnerability.

### ✅ Task 2: Password Strength Validation using Python

A Python function `is_strong_password(password: str) -> bool` was developed to ensure that user-created passwords meet strong security standards. A password is considered strong if:

- It is **6 to 20 characters** long.
- Includes **at least one lowercase**, **one uppercase**, and **one digit**.
- Does **not contain three repeating characters** in a row.

#### 📌 Example:
```python
is_strong_password("ayesh12")      # Output: False  
is_strong_password("Ayesha123@s")    # Output: True
```

---

## 📁 Assignment 2: Classical Cryptography – Product Cipher

This assignment involves encryption of a plaintext message using a **3-stage product cipher** combining Caesar, Vigenère, and Auto-key Vigenère ciphers.

### ✅ Task 1: Manual Encryption (Handwritten)

The message:
```
"ARRANGE A TRIP AFTER THE EXAMS."
```

was encrypted using the following process:

1. **Caesar Cipher** – key = 3  
2. **Vigenère Cipher** – key = First Name  
3. **Auto-key Vigenère Cipher** – key = Last Name  

Each stage enhances security by layering different cipher techniques.

### ✅ Task 2: Python Code Validation

A complete Python script was written to:

- Apply all three encryption stages in sequence.
- Validate the manually computed ciphertext using automated logic.

---

## 📁 Assignment 3: AES Key Expansion – Python Implementation


This assignment demonstrates implementation of the **AES key expansion phase**, crucial for secure symmetric encryption in modern applications.

### ✅ Implemented Functions in Python (Jupyter Notebook):

- **RotWord**: Rotates a 4-byte word left by one byte with wrapping.  
- **SubWord**: Applies S-Box substitution to each byte of the word.  
- **Round Constants (RCon)**: Generates the round constant values for each round.  

These functions help produce **44 4-byte words** from a given **128-bit AES key** for round-based encryption.

