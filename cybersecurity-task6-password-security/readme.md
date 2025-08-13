# 🔐 Task 6: Password Strength Evaluation | Cybersecurity Internship

## 📌 Objective

The aim of this task is to:
- Understand what makes a password strong.
- Test different passwords using online password strength checkers.
- Learn from password feedback and apply security best practices.
- Document the impact of password complexity on security.
- Explore common password attacks and countermeasures.

---

## 🔐 Password Samples and Strength Test

Three passwords were created for evaluation:

| Password             | Complexity Level | Characteristics                          |
|----------------------|------------------|-------------------------------------------|
| `password123`        | Weak             | Lowercase + numbers only; dictionary word |
| `Deepak@2025`        | Moderate         | Mixed case, numbers, symbol               |
| `D3eP@k!2025_S3cUr3#`| Strong           | Long, uppercase + lowercase + symbols + digits |

---

## 🧪 Testing Tool

- **Tool Used**: [https://www.passwordmeter.com](https://www.passwordmeter.com)
- **Method**: Each password was entered in the tool to analyze strength, feedback, and scoring.
- **Results**: Screenshots of the results are saved in the `screenshots/` folder.

---

## 📊 Evaluation Summary

### Weak Password: `password123`
- Feedback: Common password, predictable, short length
- Score: Very Low
- Risk: Highly vulnerable to brute force and dictionary attacks

### Moderate Password: `Deepak@2025`
- Feedback: Includes symbols and digits, but still uses name pattern
- Score: Medium
- Risk: Better, but predictable components can be exploited

### Strong Password: `D3eP@k!2025_S3cUr3#`
- Feedback: Excellent use of complexity and length
- Score: Very High
- Risk: Highly secure against brute force and dictionary attacks

---

## 🛡️ Common Password Attacks

| Attack Type         | Description |
|---------------------|-------------|
| Brute Force         | Attempts all possible combinations until success. |
| Dictionary Attack   | Tries passwords using common words from a dictionary file. |
| Phishing            | Tricks users into entering passwords on fake websites. |
| Credential Stuffing | Uses leaked username-password pairs from previous breaches. |

---

## 🧠 Key Learnings & Best Practices

- Password **length** significantly improves resistance to attacks.
- Include a **mix** of:
  - ✅ Uppercase & lowercase letters  
  - ✅ Digits  
  - ✅ Special characters  
- Avoid using:
  - ❌ Names
  - ❌ Birthdays
  - ❌ Common patterns like `123`, `qwerty`
- Use **Passphrases**:
  - Example: `Eat!Sleep_Code@2025&Repeat`
- Always enable **Multi-Factor Authentication (MFA)**.
- Use **Password Managers** to generate and store secure passwords.

---

## 🔧 Tools Recommended

- [PasswordMeter](https://www.passwordmeter.com)
- [HaveIBeenPwned](https://haveibeenpwned.com/)
- [Bitwarden](https://bitwarden.com/) (Password Manager)

---
