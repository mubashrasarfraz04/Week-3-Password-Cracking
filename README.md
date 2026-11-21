 🛡️ Password Cracking with NetworkWalks Tools

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Password%20Cracking-red?style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-2026.3-blue?style=for-the-badge)
![Hashcat](https://img.shields.io/badge/Tool-Hashcat-black?style=for-the-badge)
![John The Ripper](https://img.shields.io/badge/Tool-John%20The%20Ripper-orange?style=for-the-badge)
![PDF Cracking](https://img.shields.io/badge/Task-PDF%20Password%20Recovery-green?style=for-the-badge)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-Week%2003-purple?style=for-the-badge)

 📖 Project Overview

This project focuses on password cracking and password recovery using NetworkWalks tools and techniques in a controlled cybersecurity lab environment.

The purpose of this lab is to understand how weak passwords can be cracked quickly, and why strong passwords are important for security. All activities were performed in an isolated lab for learning and authorized testing only.

In this lab, a locked PDF file was given. First its hash was extracted, then Hashcat / John the Ripper tool was used to crack the hash and recover the password. After recovering the password, the PDF was unlocked and the hidden flag was captured.

 🎯 Objectives

The main objectives of this project are to:

- Understand the concept of password cracking and hash cracking
- Extract hash from a locked PDF file
- Use Hashcat and John the Ripper for password recovery
- Use Hash Calculator to verify hash values
- Recover the password from the locked PDF
- Unlock the PDF and capture the flag
- Document the complete cracking process

💡 Purpose of the Lab

The lab was used to provide an isolated and controlled environment for:

- Learning password security and common weak passwords
- Practicing hash extraction and cracking techniques
- Understanding dictionary attack with rockyou wordlist
- Testing PDF password protection
- Capturing the flag after successful cracking

#⚙️ Lab Configuration

| Component | Configuration |
| --- | --- |
| Security OS | Kali Linux 2026.3 |
| Tool 1 | Hashcat |
| Tool 2 | John the Ripper |
| Tool 3 | Hash Calculator |
| Target File | MyLockedPDF.pdf |
| Attack Type | Dictionary Attack |
| Wordlist | rockyou.txt |
| Network | NAT Network / Private Lab Network |

🛠️ Lab Setup Procedure

### Step 1: Analyze the Locked PDF File
First the locked PDF file `MyLockedPDF.pdf` was checked. The file was password protected and could not be opened without a password.

### Step 2: Extract Hash from PDF
The PDF file was converted into hash format using a PDF hash extraction tool, so that it could be cracked with Hashcat.

### Step 3: Verify Hash with Hash Calculator
Hash Calculator was used to check and verify the hash value of the file and to understand how hashing works.

### Step 4: Crack the Password with Hashcat
Hashcat was run with `rockyou.txt` wordlist in dictionary attack mode to crack the PDF hash and recover the original password.

### Step 5: Unlock PDF and Capture Flag
After the password was recovered, the PDF was unlocked with that password. Inside the PDF, the hidden flag was found.

✅ Example Results

| Item | Result |
| --- | --- |
| Target File | MyLockedPDF.pdf |
| Hash Type | PDF Hash |
| Cracking Tool | Hashcat / John the Ripper |
| Wordlist Used | rockyou.txt |
| Status | Password Successfully Cracked |
| Flag Captured | `nw{cybersecurity_flag_captured_2606}` |

> Flag: `nw{cybersecurity_flag_captured_2606}`

⚠️ Problems Encountered & Solutions

### Problem 1: PDF Not Opening Without Password
Solution: PDF was not opened by force. Instead its hash was extracted and then cracked in a proper way.
 Problem 2: Hashcat Taking Time
Solution: Correct hash mode was selected and `rockyou.txt` wordlist was used. After that the password was cracked quickly.

### Problem 3: Hash Verification Confusion
Solution: Hash Calculator was used to verify the hash value and to confirm the correct hash before cracking.

## 🧰 Tools & Resources

 - Hashcat: https://hashcat.net/hashcat/
- John the Ripper:https://www.openwall.com/john/
- Kali Linux: https://www.kali.org/get-kali/
- rockyou Wordlist: Built-in Kali Wordlist
- Hash Calculator: For hash verification

## 👤 Student
Mubashra




Cybersecurity Student

LinkedIn: https://www.linkedin.com/in/mubashra-khan-981805430?utm_source=share_via&utm_content=profile&utm_medium=member_android

## 📁 Project Information

**Program Name:** Cybersecurity at NetworkWalks | **Week:** 03 | **Project:** Password Cracking with NetworkWalks Tools

**Repository:** GitHub
