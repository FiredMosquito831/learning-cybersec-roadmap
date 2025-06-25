# learning-cybersec-roadmap
My journey of hopefully learning studying and understanding cybersec

Build a **strong foundation in cybersecurity**, with a focus on **system administration, ethical hacking, networking architecture**, and **Linux/Unix-based operating systems**, there are **many high-quality free resources** available. These include:

- Free online courses
- Open-source books and guides
- Interactive labs and platforms
- Virtual machines for practice (like Kali Linux)
- Capture The Flag (CTF) challenges
- Hands-on projects and walkthroughs

---

## 🎯 Learning Goals Recap:
You want to learn:
- **System Administration** (Linux/Unix focused)
- **Ethical Hacking**
- **Networking Architecture**
- **Hands-on labs and exercises**
- **Chapter-by-chapter theoretical + practical learning**
- **Free resources only**

---

# ✅ Comprehensive Free Cybersecurity Learning Path (Self-Paced)

This guide is structured into **modules**, each with:
- 📚 **Theoretical Reading**
- 💻 **Practical Exercises**
- 🧠 **Projects & Challenges**
- 🛠️ **Tools & Platforms**

---

## 🔹 MODULE 1: Introduction to Networking and Operating Systems

### 📚 Theoretical Foundations:
- **Book:** [“Networking for Systems Administrators” by Kyle Rankin](https://www.linuxnewbieguide.org/)  
  - Covers TCP/IP, DNS, DHCP, firewalls, and more.
- **Article Series:** [Linux Journey – Basics of Networking](https://linuxjourney.com/)
  - Simple, beginner-friendly lessons.

### 💻 Practical Labs:
- **Tool:** [Cisco Packet Tracer (Free Version)](https://www.netacad.com/courses/packet-tracer)
  - Simulate network topologies, routers, switches, VLANs.
- **Lab Tasks:**
  - Build a simple network with 2 PCs, 1 router, 1 switch.
  - Configure IP addresses and test connectivity.
  - Set up basic firewall rules.

### 🧠 Project:
- Create a lab where you simulate a small office network with internet access using Cisco Packet Tracer.

---

## 🔹 MODULE 2: Linux System Administration

### 📚 Theoretical Foundations:
- **Free Book:** [Linux From Scratch (LFS)](https://www.linuxfromscratch.org/)
  - Learn how Linux works from the inside out.
- **Online Course:** [Linux Journey – Full Curriculum](https://linuxjourney.com/)
  - Covers shell commands, file system structure, users/groups, permissions, etc.
- **YouTube Playlist:** [Learn Linux Tutorials – The Net Ninja](https://www.youtube.com/playlist?list=PL43pGy8vGWd5fpeFN_6vX7F5_aeVIFjzw)

### 💻 Practical Labs:
- **OS:** Install [Kali Linux](https://www.kali.org/get-kali/) or use [WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
- **Practice Commands:**
  ```bash
  ls, cd, mkdir, touch, cat, nano, chmod, chown, ps, top, systemctl
  ```
- **Lab Tasks:**
  - Create users and groups.
  - Set folder permissions.
  - Write a simple Bash script that automates a task (e.g., backs up a folder).
  - Use `journalctl` and `dmesg` to troubleshoot system logs.

### 🧠 Project:
- Build a local server (Apache/Nginx), secure it with a firewall (`ufw`), and automate backups with a cron job.

---

## 🔹 MODULE 3: Ethical Hacking / Penetration Testing

### 📚 Theoretical Foundations:
- **Book:** [“Hacking: The Art of Exploitation” (PDF available via legal sources)](https://nostarch.com/hacking)
  - Teaches C programming, assembly, memory management, and exploit development.
- **Book:** [Metasploit Unleashed (Free Online)](https://www.offensive-security.com/metasploit-unleashed/)
  - Official guide to Metasploit Framework.
- **YouTube Channel:** [IppSec](https://www.youtube.com/@ippsec)
  - Walkthroughs of real hacking scenarios.

### 💻 Practical Labs:
- **Platform:** [TryHackMe – Free Tier](https://tryhackme.com/)
  - Beginner-friendly CTF-style rooms like:
    - “Intro to Security”
    - “Nmap”
    - “OWASP Top 10”
- **Platform:** [Hack The Box – Starting Point Machines](https://app.hackthebox.com/)
  - Solve 5 beginner boxes (e.g., Red, Blue, Fawn).
- **Tools to Practice:**
  - Nmap, Gobuster, Burp Suite, Metasploit, SQLMap

### 🧠 Project:
- Complete 5 TryHackMe rooms and document your findings in a report.
- Capture flags, escalate privileges, and write up your methodology.

---

## 🔹 MODULE 4: Web Application Security & Bug Bounty Hunting

### 📚 Theoretical Foundations:
- **Book:** [The Web Application Hacker’s Handbook (Free PDF versions exist)](https://www.wiley.com/en-us/The+Web+Application+Hacker%27s+Handbook%2C+2nd+Edition-p-9781118026474)
- **Guide:** [OWASP Testing Guide v4](https://owasp.org/www-project-web-application-security-testing/)
- **Video Series:** [BugBountyHunter – Free Lessons](https://bugbountyhunter.com/)

### 💻 Practical Labs:
- **Platform:** [PortSwigger Web Security Academy](https://portswigger.net/web-security)
  - Learn about XSS, SQLi, IDOR, CSRF, etc.
  - Each topic has interactive labs.
- **Tool:** Burp Suite Community Edition (Free)
- **Tool:** ZAP Proxy (Free alternative to Burp)

### 🧠 Project:
- Find and exploit vulnerabilities in PortSwigger labs.
- Submit a vulnerability report as if it were a bug bounty submission.

---

## 🔹 MODULE 5: Malware Analysis & Reverse Engineering

### 📚 Theoretical Foundations:
- **Book:** [Practical Malware Analysis – Free PDF (via legal channels)](https://nostarch.com/malware)
- **Guide:** [MalwareTechBlog – Real-world malware analysis cases](https://malwaretechblog.com/)
- **Course:** [OpenSecurityTraining.info – Intro to RE](https://opensecuritytraining.info/IntroReverseEngineering.html)

### 💻 Practical Labs:
- **Tool:** Ghidra (NSA reverse engineering tool – FREE)
- **Tool:** x64dbg (Free debugger)
- **Tool:** VirusTotal – Upload samples for initial analysis
- **VM Setup:** Use VirtualBox to create an isolated Windows VM for malware testing.

### 🧠 Project:
- Analyze a sample malware binary using Ghidra.
- Identify strings, functions, and potential indicators of compromise (IOCs).

---

## 🔹 MODULE 6: Capture The Flag (CTF) Competitions

### 📚 Resources:
- [CTFtime.org](https://ctftime.org/) – List of upcoming CTF events
- [OverTheWire – Wargames](https://overthewire.org/wargames/)
  - Start with Bandit, Leviathan, Narnia

### 💻 Practice:
- **Bandit (OverTheWire):** Basic Linux and command-line skills
- **Leviathan:** Binary exploitation and privilege escalation
- **PicoCTF (Archive)**: [https://play.picoctf.org/](https://play.picoctf.org/)
  - Great for beginners; includes write-ups after solving
- **CryptoHack**: [https://cryptohack.org/](https://cryptohack.org/)
  - Learn cryptography through gamified challenges

### 🧠 Project:
- Participate in a beginner-level CTF (e.g., vsCTF, picoCTF, Hack The Box Starting Point)
- Document your process and solutions in a blog or GitHub repo.

---

## 🔹 Bonus Tools & Resources

| Tool | Purpose | Link |
|------|---------|------|
| **Kali Linux** | All-in-one penetration testing OS | https://www.kali.org/get-kali/ |
| **VirtualBox** | Free virtualization tool | https://www.virtualbox.org/wiki/Downloads |
| **VulnHub** | Download vulnerable VMs | https://www.vulnhub.com/ |
| **HTB Academy (Free Tier)** | Guided ethical hacking lessons | https://academy.hackthebox.com/ |
| **Cybrary – Free Courses** | Cybersecurity fundamentals | https://www.cybrary.it/ |
| **freeCodeCamp – Cybersecurity** | Articles, tutorials, videos | https://www.freecodecamp.org/news/tag/cybersecurity/ |

---

## 📅 Suggested 12-Week Self-Paced Study Plan (FREE)

| Week | Focus Area | Resources |
|------|------------|-----------|
| 1–2 | Networking & Linux Basics | Linux Journey, Cisco PT, Kali CLI |
| 3–4 | Linux Admin & Scripting | LFS book, Bash scripting, systemd |
| 5–6 | Ethical Hacking Intro | TryHackMe, HTB Starting Point, Metasploit Unleashed |
| 7–8 | Web App Security | PortSwigger, OWASP, Burp Suite |
| 9–10 | Malware Analysis | Practical Malware Analysis, Ghidra |
| 11–12 | CTF Challenges | OverTheWire, PicoCTF, HTB |

> 📝 Tip: Keep a journal or GitHub repo of all your labs, notes, screenshots, and scripts.

---

## 🧾 Summary of Free Resources

| Type | Resource |
|------|----------|
| **Books** | Hacking: The Art of Exploitation, Practical Malware Analysis, Linux From Scratch |
| **Courses** | Linux Journey, Cybrary, TryHackMe Free Rooms |
| **Platforms** | TryHackMe, Hack The Box (Starting Point), PortSwigger, VulnHub |
| **Tools** | Kali Linux, VirtualBox, Ghidra, Wireshark, Burp Suite CE |
| **CTFs** | OverTheWire, PicoCTF, CryptoHack, vsCTF |

---

## 🚀 Final Tips for Success

- **Set weekly goals** and track progress.
- **Use version control (Git/GitHub)** to store notes, scripts, and walkthroughs.
- **Join Discord communities** like TryHackMe, Hack The Box, or r/netsecstudents.
- **Document everything** — this becomes your portfolio.
- **Stay consistent** — even 1 hour/day can lead to mastery over time.

---
