# Week3-Cybersecurity-and-Ethical-hacking
# Password Cracking Lab: Week 3

**Cybersecurity & Ethical Hacking Internship | Networkwalks**

This repository documents my Week 3 practical tasks on password security. I recovered a password from an encrypted PDF using two different toolchains and compared the results.

 **Disclaimer:** This work was done in a controlled lab environment on files I created myself, for educational purposes only. Never attempt password cracking on systems or files you do not own or have explicit permission to test.

---

## 📌 Objectives

- Understand how password hashes are extracted from protected files
- Perform a dictionary attack to recover a password from a hash
- Compare a desktop toolchain with a browser-based toolchain
- Learn what makes a password resistant to cracking

---

## 🛠️ Tools Used

| Project Module | Tools |
|---|---|
| **PM1** | John the Ripper (JtR), Johnny (GUI for JtR), Windows PC |
| **PM2** | Networkwalks Hash Calculator, Networkwalks Password Cracker, Web Browser |

---

## 🧪 Methodology

### Project Module 1: John the Ripper + Johnny (GUI)

1. Installed and configured John the Ripper and Johnny on Windows
2. Extracted the password hash from an encrypted PDF
3. Loaded the hash into Johnny
4. Ran a dictionary attack to recover the password
5. Verified the recovered password by opening the PDF

### Project Module 2: Networkwalks Browser-Based Tools

1. Uploaded a password-protected PDF to the **Hash Calculator**
2. Extracted and copied the complete PDF hash value
3. Opened the **Password Cracker** and pasted the hash
4. Started the cracking process
5. Recovered the password and verified it by opening the PDF


---

## 📊 Results

| Module | Approach | Outcome |
|---|---|---|
| PM1 | Desktop (JtR + Johnny) | Password recovered via dictionary attack |
| PM2 | Browser-based (Networkwalks tools) | Password recovered via dictionary attack |

Both passwords were cracked almost instantly because they were simple, common words.

---

## 💡 Key Learnings

- How password hash extraction works
- How the basic password recovery process works (hash extraction → dictionary attack)
- The core idea is the same whether you use professional desktop tools or lightweight web tools
- **Password strength, not the sophistication of the attacker's tools, is what protects sensitive data**

---

## 🛡️ Defensive Takeaways

- Use long, unpredictable passwords or passphrases
- Avoid common words and dictionary terms
- Use a password manager to generate and store strong passwords
- Enable multi-factor authentication wherever possible

---

## 📁 Repository Structure



## 👤 Author

**Tapiwanashe Ripondo**
Cybersecurity Intern, Networkwalks
BSc Honours in Information Technology, Chinhoyi University of Technology

---

## 🙏 Acknowledgements

Thanks to **Networkwalks** and **Waqas Karim (CCIE)** for the structured, hands-on training.

#CyberSecurity #EthicalHacking #PasswordCracking #JohnTheRipper #HashExtraction #Networkwalks
