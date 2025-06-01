# 🏦 BANK HACKED - TryHackMe CTF Writeup

Back in Aug 2023, I completed my first Capture The Flag challenge on TryHackMe.

## 🔍 What I did:
- Used `gobuster` for directory brute-forcing
- Explored hidden web directories
- Learned how attackers enumerate web apps
- Gained first practical exposure to offensive security

---

### 🛠 Tool Used: Gobuster

```bash
gobuster dir -u http://<target-ip> -w /usr/share/wordlists/dirb/common.txt
