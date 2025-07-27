# PenteraX 🛡️

A complete **offensive security lab** simulating an **EdTech enterprise** designed for real-world **penetration testing** and **red teaming** practice.

---

## 📁 Project Structure

This lab is hosted on VirtualBox and includes:
- **Kali Linux** (Attacker Machine)
- **Ubuntu Server** (Web Server running Apache)
- **Metasploitable 2** (Vulnerable Target)
- **Windows 10** (Admin or Client)
- More VMs to be added: Active Directory, vulnerable APIs, etc.

---

## ✅ Features Completed So Far

- 🔹 Apache server setup on Ubuntu
- 🔹 Custom EdTech Homepage (`padholikho.com`)
- 🔹 Logo uploaded and integrated
- 🔹 Login form with CAPTCHA
- 🔹 Username/Password verification with file-based storage
- 🔹 Login attempt tracking with timestamp logs
- 🔹 Connected GitHub repo and pushed code

---

## 🚧 Features In Progress

- [ ] Role-based dashboards (HR, Sales, Admin)
- [ ] SQLi-vulnerable pages
- [ ] XSS, CSRF and brute-force login simulation
- [ ] User enumeration and error-based injection testing
- [ ] DDoS attack simulation

---

## 💻 Lab Access Details

- Web app running on: `http://<Ubuntu-VM-IP>/index.html`
- Files located at: `/var/www/html/` on Ubuntu server

---
📊 Directory Overview

/var/www/html/
├── index.html                 # Main homepage of padholikho.com
├── logo.png                   # Brand logo
├── login.html                 # Login form with CAPTCHA
├── users.txt                  # File storing valid username-password pairs
├── logins.txt                 # Login attempt logs with timestamps
├── captcha.js                 # Simple CAPTCHA implementation
└── style.css                  # Basic styling


