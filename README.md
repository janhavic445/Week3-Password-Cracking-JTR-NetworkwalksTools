
# 🔐 Password Cracking with John the Ripper and Networkwalks Tools

## 📌 Overview

This project covers two password-cracking exercises assigned during Week 3 of the Networkwalks Cybersecurity & Ethical Hacking Training.

The exercises demonstrate password hash extraction and dictionary-based password recovery using cybersecurity tools.

## 🎯 Objective

- Extract password hashes from protected PDF files.
- Perform dictionary attacks.
- Recover passwords and unlock protected PDFs.
- Understand practical password security techniques.

## 🛠️ Tools Used

- John the Ripper (John + Johnny GUI)
- Online Hash Crack (PDF Hash Extractor)
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Microsoft Word

---

# 🚀 Exercise 1: John the Ripper

### Workflow

1. Extract the password hash from the protected PDF.
2. Save the extracted hash into a text file.
3. Use John the Ripper with a dictionary wordlist.
4. Run the password-cracking process.
5. Verify the recovered password by opening the PDF.

### Commands

```bash
john --wordlist=<wordlist_path> <hash_file>
```

To display recovered passwords:

```bash
john --show <hash_file>
```

---

# 🚀 Exercise 2: Networkwalks Tools

### Step 1: Extract Password Hash

Use the Networkwalks Hash Calculator to extract the hash from the protected PDF.

### Step 2: Crack the Password

Enter the extracted hash into Networkwalks Password Cracker and perform the dictionary attack.

### Step 3: Password Cracked Successfully!

The tool successfully recovered the PDF password.

**Recovered Password:**

```text
password1
```

### Screenshot

![Password Cracked Successfully](screenshots/02-password-cracked-successfully.png.jpeg)

---

# 🏆 Captured Flags

### Flag 1

The first PDF confirmation screen displayed the following captured flag:

```text
nw{cybersecurity_flag_captured_2608}
```

![First Flag Captured](screenshots/01-networkwalks-flag-captured.png.jpeg)

### Flag 2

The second PDF confirmation screen displayed the following flag:

```text
nw{networkwalks_flag1_jr_270521_1}
```

![Second Flag Captured](screenshots/03-networkwalks-flag-1.png.jpeg)

---

# 📚 Key Learnings

- Understanding password hash extraction.
- Practical experience with password-cracking tools.
- Learning dictionary-based attacks.
- Exploring Networkwalks cybersecurity tools.
- Understanding PDF password protection.
- Developing practical ethical hacking skills.

---

# ⚠️ Disclaimer

This project was completed for educational purposes as part of the Networkwalks Cybersecurity & Ethical Hacking Training.

All password auditing activities should only be performed on files and systems for which you have explicit authorization.

---

**Author:** Cybersecurity & Ethical Hacking Trainee
