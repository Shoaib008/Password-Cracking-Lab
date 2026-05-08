# Ethical Password Cracking and Hash Security Analysis using Hashcat

## Project Overview
This project demonstrates ethical password cracking and hash analysis using Hashcat in a controlled local cybersecurity lab environment.

The project simulates how weak passwords can be cracked using dictionary attacks against MD5 hashes.

## Tools Used
- Hashcat
- Windows PowerShell
- MD5 Hashing
- Wordlists
- Command Line Interface (CLI)

## Project Workflow
1. Created a sample password
2. Generated MD5 hash using certutil
3. Stored hash in a hash file
4. Created custom wordlist
5. Used Hashcat to perform dictionary attack
6. Successfully recovered the password

## Hashcat Command Used

```powershell
.\hashcat -m 0 -a 0 md5hash.txt words.txt
