# cybersecurity-lab
---

# Beginner Cybersecurity Lab (Attack & Defend)

A hands-on cybersecurity project built in a safe, isolated virtual environment.
This lab uses **Kali Linux (attacker)** and a **vulnerable machine (victim)** to practice scanning, exploitation, and system hardening.

---

##  Lab Architecture

This project uses a simple, isolated lab environment built within VirtualBox.

![Lab Architecture](Diagram/Cybersecurity_Diagram.drawio.png)

The architecture consists of two virtual machines:

* **Attacker VM:** A Kali Linux instance, which comes pre-loaded with a full suite of security and penetration testing tools.
* **Victim VM:** A Metasploitable 2 instance, an intentionally vulnerable version of Linux designed for security training and testing.

Both VMs are connected exclusively to a **VirtualBox Internal Network (VBoxNet)**. This isolates the lab, preventing the vulnerable machine from being exposed to the public internet and keeping all attack traffic safely contained.

---

## Tools Used

* **VirtualBox** (or VMware Player)
* **Kali Linux** – attacker machine
* **Metasploitable / Vulnerable Windows VM** – victim machine
* **Nmap, Metasploit, Hydra, Burp Suite, etc.**

---

## Project Overview

### **Goal of This Lab**

* Practice identifying vulnerabilities
* Learn how attacks work (recon, enumeration, exploitation)
* Apply security fixes and hardening
* Build real, demonstrable cybersecurity experience

### **What This Project Demonstrates**

* Understanding of basic pentesting methodology
* Knowledge of open ports, protocols, and services
* Ability to secure a vulnerable system
* Cybersecurity mindset and documentation skills

---

## Phase 1 — Reconnaissance & Scanning (Upcoming)

All notes and screenshots will be stored in:

```
/screenshots/recon  
/docs/recon  
```

**Planned tasks:**

* Discover target VM on internal network
* Run Nmap scans (`-sV`, `-A`, etc.)
* Identify open ports + services
* Document findings

---

## Phase 2 — Exploitation (Upcoming)

All notes and screenshots will be stored in:

```
/screenshots/exploitation  
/docs/exploitation  
```

**Planned tasks:**

* Research vulnerabilities
* Use Metasploit or manual exploitation
* Gain low-privilege access
* Document exploit steps clearly

---

## Phase 3 — Fixing & Hardening (Upcoming)

All notes and screenshots will be stored in:

```
/screenshots/hardening  
/docs/hardening  
```

**Planned tasks:**

* Close unnecessary ports/services
* Patch vulnerable applications
* Improve authentication & permissions
* Validate fixes with rescans

---

##  Lessons Learned (Will Update Over Time)

* Understanding enumeration & recon
* Importance of isolating vulnerable systems
* Mapping vulnerabilities to mitigations
* Thinking like an attacker to defend effectively

---

##  Disclaimer

This project was conducted in a **fully isolated, offline virtual environment** for educational purposes only.
No scanning, exploitation, or testing was performed on real devices or external networks.

---

## Project Structure

```
cybersecurity-lab/
│
├── README.md
├── diagrams/
├── screenshots/
│   ├── recon/
│   ├── exploitation/
│   └── hardening/
├── docs/
│   ├── recon/
│   ├── exploitation/
│   └── hardening/
└── scripts/   (optional)
```

---
