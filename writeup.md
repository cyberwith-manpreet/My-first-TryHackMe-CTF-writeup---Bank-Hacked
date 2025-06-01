# BANK HACKED! 🏦💻  
*TryHackMe CTF – Directory Bruteforce using Gobuster*

---

## Introduction

Back in August 2023, at the beginning of my 2nd year, I started my cybersecurity journey by completing my very first Capture The Flag (CTF) challenge on TryHackMe. This challenge introduced me to offensive security concepts and practical tools used for web reconnaissance.

---

## Objective

The goal was to perform directory brute-forcing on a target website to discover directories or files that are not visible by default.

---

## Tools Used

- **Gobuster**: A directory/file brute-forcing tool used to find hidden paths on web servers.

---

## What I Did

1. Ran Gobuster against the target website to enumerate hidden directories.
2. Discovered a hidden directory and files that could be used to further explore and exploit the site.
3. Understood how attackers gather information about a website’s structure before launching attacks.

---

## Commands Used

```bash
gobuster dir -u http://[target_IP] -w /usr/share/wordlists/dirb/common.txt

---
