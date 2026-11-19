🔐 Networkwalks – Password Cracking Labs
Hands-on password security testing using John the Ripper (JTR) and Networkwalks Tools.

📌 Project Overview
This repository documents my hands-on password cracking exercises completed as part of the Networkwalks Cybersecurity Training Program – Week 3.

The project focuses on understanding how password cracking works, extracting password hashes from protected PDF documents, and recovering passwords using different password-cracking tools.

The practical work consists of two essential modules:

W3-PM1: Password Cracking with John the Ripper (JTR).
W3-PM2: Password Cracking with Networkwalks Tools.
Both exercises demonstrate how weak passwords can be recovered through password-cracking techniques and highlight the importance of using strong passwords to protect sensitive information.

🎯 Objectives
The main objectives of these practical exercises were to:

Understand the fundamentals of password cracking and password hashes.
Learn how password-protected PDF files store password verification data.
Extract PDF password hashes using hash extraction tools.
Use John the Ripper to perform password cracking.
Understand and use Johnny, the graphical interface for John the Ripper.
Use Networkwalks Hash Calculator to extract PDF hashes.
Use Networkwalks Password Cracker to recover passwords.
Verify recovered passwords by opening protected PDF documents.
Understand the importance of strong password security.
🛠️ Project Modules
1. W3-PM1 – Password Cracking with John the Ripper (JTR)
Objective:

Recover the password of a protected PDF document using John the Ripper and Johnny GUI on a Windows PC.

Tools Used:

John the Ripper (JTR)
Johnny GUI
Online Hash Extractor
Notepad
Windows
Procedure:

Download and install John the Ripper on Windows.
Download and install Johnny GUI.
Configure Johnny by selecting the john.exe executable from the JTR installation directory.
Download the password-protected PDF document.
Upload the PDF to an online PDF hash extractor.
Extract and copy the generated PDF hash.
Save the extracted hash in a text file named hash1.txt.
Open Johnny and load the saved password hash file.
Start a new password-cracking attack.
Wait for the cracking process to complete and retrieve the recovered password.
Open the protected PDF using the recovered password.
Key Learning:

Learned how John the Ripper processes password hashes and how Johnny GUI simplifies password-cracking operations through a graphical interface.

Screenshots:
Commited the screenshots

2. W3-PM2 – Password Cracking with Networkwalks Tools
Objective:

Recover the password of a protected PDF document using the Networkwalks Hash Calculator and Password Cracker.

Tools Used:

Networkwalks Hash Calculator
Networkwalks Password Cracker
Web Browser
Windows
Procedure:

Download the password-protected PDF document from the Networkwalks lab page.
Open the Networkwalks Hash Calculator.
Upload the protected PDF document.
Extract the generated PDF hash starting with $pdf$.
Copy the complete hash value.
Open the Networkwalks Password Cracker.
Paste the extracted hash into the password cracker.
Start the password-cracking process.
Wait for the tool to identify the matching password.
Open the protected PDF document using the recovered password.
Key Learning:

Understood how browser-based hash extraction and password-cracking tools work together to recover passwords from protected PDF documents without installing additional software.

Screenshots:
Commited the screenshots

⚙️ Tools & Technologies
Tool	Purpose
John the Ripper	Password hash cracking
Johnny GUI	Graphical interface for JTR
Networkwalks Hash Calculator	PDF hash extraction
Networkwalks Password Cracker	Password recovery
Windows	Lab environment
Web Browser	Accessing online tools
🧠 Key Concepts Learned
1. Password Cracking
Password cracking is the process of recovering passwords by testing possible password candidates against stored password hashes or protected-file verification data.

2. Hash Extraction
Hash extraction involves obtaining the password-related hash data from a protected file so that it can be processed by a compatible password-cracking tool.

3. John the Ripper
John the Ripper is a password security auditing and recovery tool that supports multiple hash formats and password-protected file types.

4. Johnny GUI
Johnny provides a graphical interface for John the Ripper, making it easier to load password files, configure attacks, and monitor cracking progress.

5. Networkwalks Password Cracking Tools
The Networkwalks Hash Calculator and Password Cracker provide browser-based functionality for extracting PDF hashes and attempting password recovery.

6. Password Security
The exercises demonstrated why weak and commonly used passwords are vulnerable to password-cracking techniques. Strong, unique passwords help improve security.

💡 What I Learned
Through these practical exercises, I gained hands-on experience with password-cracking techniques and learned how different tools can be used to recover passwords from protected PDF documents.

The key takeaways include:

Understanding the relationship between password protection and hash extraction.
Using John the Ripper for password security testing.
Working with Johnny GUI to simplify JTR operations.
Performing password recovery using browser-based Networkwalks tools.
Understanding how password complexity affects cracking time.
Recognizing the importance of strong and unique passwords.
These exercises strengthened my understanding of password security, hash extraction, and practical cybersecurity testing.

🔐 Security & Ethical Use
These exercises were performed for educational purposes as part of cybersecurity training.

Password-cracking tools should only be used on files and systems that you own or have explicit authorization to test.

Unauthorized password recovery or access to protected files is not permitted.
