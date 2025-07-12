# PenteraX 🔥

**PenteraX** is a fully offline, self-hosted cybersecurity lab built inside VirtualBox. It simulates a vulnerable EdTech enterprise named `padholikho.com`, complete with users, departments, servers, and an attacker machine.

## 🔧 Lab Components

- Kali Linux (Attacker)
- Ubuntu Server (Web + DB Hosting for padholikho.com)
- Windows 10 (Client/HR)
- Windows Server 2019 (Domain Controller - padholikho.local)
- Metasploitable 2 (Vulnerable Server)

## 🎯 Attacks Performed

- SQL Injection (Login Bypass)
- XSS (Reflected and Stored)
- Brute Force Login (Hydra)
- DDoS Simulation (hping3, slowloris)
- AD Attacks (Kerberoasting, Pass-the-Hash)

## 📂 Folder Structure

```bash
/docs          → Lab setup notes, architecture  
/website       → EdTech website source code (padholikho.com)  
/attacks       → Step-by-step attack walkthroughs  
/configs       → Apache, MySQL, AD, and hosts configs  
/screenshots   → Proof of attacks and setups  
