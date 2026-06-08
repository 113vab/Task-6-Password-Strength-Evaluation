# Task 6: Password Strength Evaluation

## Objective

The objective of this task was to understand the importance of strong passwords by testing passwords of varying complexity using an online password strength evaluation tool. The task also aimed to analyze how password length, complexity, and predictability affect security against common password-cracking attacks.

---

# Introduction

Passwords are the first line of defense for protecting digital accounts and sensitive information. Weak passwords can be easily guessed or cracked by attackers using automated tools, while strong passwords significantly increase account security.

In this task, multiple passwords were tested using a password strength checker. The results were analyzed to understand how different password characteristics influence security.

---

# Tools Used

* Password Meter (Online Password Strength Checker)
* Web Browser
* Screenshot Tool

---

# Passwords Tested

### 1. Password: `password123`

**Strength Rating:** Very Weak

#### Observations

* Contains a commonly used dictionary word.
* Uses a predictable number sequence.
* Frequently appears in leaked password databases.
* Can be cracked almost instantly.

#### Result

The password meter classified this password as **Very Weak** and indicated that it could be compromised immediately through common attack methods.

---

### 2. Password: `Vaibhav123`

**Strength Rating:** Weak

#### Observations

* Contains a personal name.
* Uses a predictable numerical pattern.
* Vulnerable to dictionary and targeted attacks.
* Slightly stronger than common passwords but still insecure.

#### Result

The password meter classified this password as **Weak** because it relies on predictable information that can be guessed by attackers.

---

### 3. Password: `Vaibhav@2026`

**Strength Rating:** Fair

#### Observations

* Includes uppercase and lowercase letters.
* Contains a special character.
* Uses a year, making it partially predictable.
* Better complexity than previous passwords.

#### Result

The password meter classified this password as **Fair**. Although stronger than the previous examples, it still contains predictable elements that reduce security.

---

### 4. Password: `V@iBh@v#2026!Cyber$ecurity`

**Strength Rating:** Very Strong

#### Observations

* Long password length.
* Combination of uppercase and lowercase letters.
* Includes numbers and multiple special characters.
* Uses diverse character types.
* Extremely difficult to brute-force.

#### Result

The password meter classified this password as **Very Strong** and estimated an exceptionally long cracking time.

---

# Password Strength Comparison

| Password                   | Strength    |
| -------------------------- | ----------- |
| password123                | Very Weak   |
| Vaibhav123                 | Weak        |
| Vaibhav@2026               | Fair        |
| V@iBh@v#2026!Cyber$ecurity | Very Strong |

---

# Understanding Common Password Attacks

## 1. Brute Force Attack

A brute force attack systematically attempts every possible character combination until the correct password is discovered.

### Prevention

* Use long passwords.
* Enable MFA.
* Use special characters.

---

## 2. Dictionary Attack

Attackers use lists of common passwords and words to guess passwords quickly.

### Prevention

* Avoid common words.
* Use random combinations.
* Use passphrases.

---

## 3. Credential Stuffing

Attackers use passwords leaked from previous data breaches to access other accounts.

### Prevention

* Use unique passwords for every account.
* Use a password manager.

---

## 4. Phishing

Users are tricked into revealing passwords through fake websites or emails.

### Prevention

* Verify website authenticity.
* Enable MFA.
* Avoid suspicious links.

---

# Password Security Best Practices

1. Use at least 12–16 characters.
2. Include uppercase letters.
3. Include lowercase letters.
4. Use numbers.
5. Use special characters.
6. Avoid names and birthdays.
7. Avoid common words.
8. Use unique passwords for every account.
9. Enable Multi-Factor Authentication (MFA).
10. Store passwords using a trusted password manager.

---

# What is MFA?

Multi-Factor Authentication (MFA) requires users to verify their identity using multiple methods.

Examples:

* Password
* OTP
* Authenticator App
* Biometric Verification

Benefits:

* Adds an extra security layer.
* Prevents unauthorized access.
* Protects accounts even if passwords are leaked.

---

# Findings

The experiment clearly demonstrated that password strength increases significantly when:

* Password length increases.
* Character variety increases.
* Predictable information is removed.
* Special characters are included.

Weak passwords were vulnerable to immediate compromise, while strong passwords required extremely large amounts of time and computational effort to crack.

---

# Conclusion

This task provided practical experience in evaluating password security. Testing multiple passwords demonstrated how password complexity directly impacts resistance to cyberattacks. Strong passwords combined with MFA provide significantly better protection against unauthorized access and modern password-cracking techniques.

The exercise emphasized the importance of creating unique, complex, and lengthy passwords for all online accounts.
