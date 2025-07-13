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


/docs          → Lab setup notes, architecture  
/website       → EdTech website source code (padholikho.com)  
/attacks       → Step-by-step attack walkthroughs  
/configs       → Apache, MySQL, AD, and hosts configs  
/screenshots   → Proof of attacks and setups

## 📦 Tools Used


- VirtualBox
- Kali Linux
- Ubuntu Server 22.04
- Apache2
- Windows 10
- NAT Network: `Hack_laB` (192.168.1.0/24)


## 🌐 Network Overview

| VM Role        | OS               | IP Address       | Description                   |
|----------------|------------------|------------------|-------------------------------|
| Attacker       | Kali Linux       | 192.168.1.x       | Launches attacks              |
| Web Server     | Ubuntu Server    | 192.168.1.7       | Hosts `padholikho.com` website |
| Client/User    | Windows 10       | 192.168.1.x       | Simulates end-user behavior   |
