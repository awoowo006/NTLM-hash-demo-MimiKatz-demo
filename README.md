# 🔐 NTLM Hash Extraction & Password Cracking Demo

## 📖 Overview
This project demonstrates a classic security attack where we:
- Extract NTLM hashes from Windows memory using Mimikatz
- Crack the hashes with John the Ripper on Kali Linux
- Demonstrate the importance of strong passwords

## ⚡ Quick Start
```bash
# Clone the repository
git clone https://github.com/awcowo006/ntlm-hash-demo.git
cd ntlm-hash-demo

🔧 Prerequisites
Windows VM (2012 or newer)

Kali Linux VM

Mimikatz tool

rockyou.txt wordlist

📊 Results
John the Ripper cracked the NTLM hash in under 1 second, returning the password:
sunshine

⚠️ Disclaimer
For educational purposes only. Use only in environments you own or have permission to test.
