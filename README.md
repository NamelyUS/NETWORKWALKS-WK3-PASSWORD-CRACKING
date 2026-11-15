
# NetworkWalks – Week 3: Password Cracking

**Intern:** Umer Shahid  
**Program:** Cybersecurity & Ethical Hacking Internship  
**Organization:** NetworkWalks  
**Week:** 3  
**Date:** 16 November 2026

## Overview

This repository contains my practical work for Week 3 of the NetworkWalks Cybersecurity & Ethical Hacking Internship.

The week's assignments focused on password cracking and understanding how passwords stored in protected PDF files can be recovered through hash extraction and password-testing techniques.

I completed two project modules using different tools and environments. Both exercises involved working with a password-protected demonstration PDF supplied for the internship.

## Project Module 1 – Password Cracking with John the Ripper

**Environment:** Kali Linux

For the first task, I used John the Ripper (JTR), a command-line password-cracking tool.

### Tools Used
- Kali Linux
- John the Ripper
- pdf2john.pl
- rockyou.txt wordlist

### Work Performed
- Located the supplied password-protected PDF in the VirtualBox shared folder.
- Extracted its password hash using `pdf2john.pl`.
- Saved the extracted hash in a text file.
- Used the `rockyou.txt` wordlist to perform a dictionary attack with John the Ripper.
- Verified the recovered password using John's `--show` option.
- Successfully opened the protected PDF and located the flag inside it.

### Key Learning
I learned how to extract PDF password hashes, use wordlists for dictionary attacks, and verify recovered passwords using John the Ripper.

**Detailed documentation:**  
[Project Module 1 – Practical Lab Report](Project-Module-1-John-the-Ripper/Umer_Shahid_NetworkWalks_Week3_PM1_Report.pdf)

---

## Project Module 2 – Password Cracking with NetworkWalks Tools

**Environment:** Windows Laptop / Web Browser

For the second task, I used two browser-based tools developed by NetworkWalks to extract and crack the password of the supplied PDF.

### Tools Used
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Web Browser

### Work Performed
- Downloaded the supplied password-protected PDF.
- Uploaded the PDF to the NetworkWalks Hash Calculator.
- Extracted and copied the complete PDF hash.
- Opened the NetworkWalks Password Cracker.
- Submitted the extracted hash and started the cracking process.
- Retrieved the recovered password.
- Opened the protected PDF using the recovered password to verify the result.

### Key Learning
I gained practical experience using browser-based password-cracking utilities and understood how hash extraction and password recovery work together.

**Detailed documentation:**  
[Project Module 2 – Practical Lab Report](Project-Module-2-NetworkWalks-Tools/Umer_Shahid_NetworkWalks_Week3_PM2_Report.pdf)

---

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Linux-based lab environment |
| John the Ripper | Password cracking |
| pdf2john.pl | PDF password-hash extraction |
| rockyou.txt | Password wordlist |
| NetworkWalks Hash Calculator | Online PDF hash extraction |
| NetworkWalks Password Cracker | Online password recovery |

## Overall Learning Outcomes

Through these two practical exercises, I developed a better understanding of:

- Password hashing and hash extraction.
- Wordlist-based dictionary attacks.
- Using John the Ripper in Kali Linux.
- Working with browser-based password-cracking tools.
- Verifying recovered passwords by opening protected documents.
- The importance of using strong, unique passwords.

The exercises also helped me compare command-line and browser-based approaches to password cracking.

## Repository Structure

```text
NETWORKWALKS-WK3-PASSWORD-CRACKING/
│
├── README.md
│
├── Project-Module-1-John-the-Ripper/
│   └── Umer_Shahid_NetworkWalks_Week3_PM1_Report.pdf
│
└── Project-Module-2-NetworkWalks-Tools/
    └── Umer_Shahid_NetworkWalks_Week3_PM2_Report.pdf
```

## Acknowledgement

These exercises were completed as part of the NetworkWalks Cybersecurity & Ethical Hacking Internship.

All practical testing was performed on the demonstration files provided for the internship.

---

**Umer Shahid**  
Cybersecurity Student | FAST-NUCES Karachi

**NetworkWalks – Week 3 | Project Modules 1 & 2**
