
# 🔐 Password Cracking with John the Ripper and Networkwalks Tools

## 📌 Overview
This project covers two password-cracking exercises assigned during Week 3 of the Networkwalks Cybersecurity & Ethical Hacking Training.

Both exercises demonstrate how to extract password hashes from protected PDF files and recover passwords using dictionary attacks.

## 🎯 Objective
- Extract password hashes from password-protected PDF files.
- Perform dictionary attacks using password-cracking tools.
- Recover passwords and unlock protected PDF files.
- Understand practical password security and ethical hacking techniques.

## 🛠️ Tools Used
- John the Ripper
- Johnny GUI
- Online Hash Crack (PDF Hash Extractor)
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Microsoft Word

## 🚀 Exercise 1: John the Ripper

### Workflow
1. Extract the password hash from the protected PDF using Online Hash Crack.
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

## 🚀 Exercise 2: Networkwalks Tools

### Workflow
1. Open Networkwalks Hash Calculator.
2. Extract the password hash from the protected PDF.
3. Enter the hash into Networkwalks Password Cracker.
4. Perform the dictionary attack.
5. Recover the password and unlock the PDF.

### Result

**Password Cracked Successfully!**

```text
password1
```

## 🏆 Captured Flags

**Flag 1:**
```text
nw{cybersecurity_flag_captured_2608}
```

**Flag 2:**
```text
nw{networkwalks_flag1_jr_270521_1}
```

## 📚 Key Learnings

- Understanding password hash extraction.
- Practical experience with John the Ripper.
- Learning dictionary-based password attacks.
- Exploring browser-based password-cracking tools.
- Understanding PDF password protection.
- Developing practical cybersecurity and ethical hacking skills.

## 👩‍💻 Author
Cybersecurity & Ethical Hacking Trainee

## ⚠️ Disclaimer
This project was completed for educational purposes as part of cybersecurity training. Password auditing should only be performed on files and systems for which you have explicit authorization.
