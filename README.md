# Task 6 – Password Strength Evaluation

## Objective
To understand what makes a password strong, evaluate different passwords using an online password strength checker, and learn about common password attacks and best practices for secure password creation.

---

## Passwords Tested & Results

| Password                 | Score  | Complexity    | Feedback Summary |
|--------------------------|--------|--------------|------------------|
| `hello123`               | 37%    | Weak         | Lacks uppercase, symbols; common word; short length |
| `Hello123`               | 63%    | Strong       | Better mix of case and numbers; still lacks symbols |
| `H3llo_123`              | 82%    | Very Strong  | Good length and mix; could be longer |
| `H3ll0_W0rld!2025`       | 100%   | Very Strong  | Excellent mix of characters, length, and complexity |
| `Mango$Tiger^Sunset!98`  | 100%   | Very Strong  | Passphrase style, long, uses words + symbols + numbers |

---

## Key Observations
1. **Length Matters** – Longer passwords are exponentially harder to crack.
2. **Character Variety** – Mixing uppercase, lowercase, numbers, and symbols increases strength.
3. **Avoid Predictability** – Common words, sequences (`1234`), and patterns reduce security.
4. **Passphrases** – Combining random unrelated words with numbers/symbols creates strong yet memorable passwords.

---

## Common Password Attacks

### 1. Brute Force Attack
Tries all possible character combinations until the password is guessed.  
- Weak password: Cracked in seconds.  
- Strong password: Could take years or centuries.

### 2. Dictionary Attack
Uses a list of common words and variations to guess passwords.  
Example: `password123`, `iloveyou`.

### 3. Credential Stuffing
Uses leaked username/password pairs from previous breaches.  
**Tip:** Use unique passwords for each account.

### 4. Phishing
Tricks the user into entering credentials on a fake site.  
**Tip:** Check URLs and enable multi-factor authentication.

---

## Best Practices for Creating Strong Passwords
- Use at least **12–16 characters**.
- Mix **uppercase, lowercase, numbers, and symbols**.
- Avoid personal details (birthdays, names).
- Use **passphrases** for easier memorization.
- Never reuse passwords across accounts.
- Use a **password manager** (e.g., Bitwarden, KeePass).
- Enable **multi-factor authentication (MFA)**.

---

## Conclusion
Passwords with **high complexity, greater length, and unpredictability** are significantly more secure.  
**Passphrases** are the best balance between security and memorability.

---

📌 **Tools Used:** [PasswordMeter.com](https://passwordmeter.com/)  
📂 **Repository Contents:**  
- `README.md` – This report.  
- `screenshots/` – Test results screenshots.
