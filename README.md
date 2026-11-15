# 🐞 Bug Bounty Beginner's Roadmap

<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-Learning-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Bug%20Bounty-Roadmap-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge" />
</p>

<p align="center">
  <b>Learn • Practice • Discover • Report • Improve</b>
</p>

Welcome to my Bug Bounty Beginner's Roadmap!

I'm Asim Sapkota, a software developer with experience and interests in:

🐍 Python and Django

💻 C# and .NET Development

🎮 Unity Game Development

🌐 Web and Backend Development

I'm passionate about building software, exploring new technologies, and continuously improving my technical skills.

Alongside software development, I'm exploring Cybersecurity, Ethical Hacking, and Bug Bounty Hunting to understand how applications work internally, identify security weaknesses, and build more secure software.

I created this repository to document my cybersecurity learning journey and collect useful resources, tools, methodologies, and practical exercises that can help beginners enter the world of **Bug Bounty Hunting**.

Whether you're a student, software developer, IT enthusiast, or someone starting from scratch, this roadmap will help you understand what to learn, where to practice, and how to develop the skills required to become a security researcher.

This repository will continue to evolve as I learn new techniques, discover useful resources, and explore real-world security challenges.

> **Important Note:** Bug bounty hunting is becoming increasingly competitive. Automated scanners and AI-powered tools can identify many common vulnerabilities, making simple findings less valuable and more likely to be duplicates. Understanding application logic, identifying business logic flaws, and developing your own testing methodology are increasingly important.

---

# 📚 Table of Contents

- [Introduction](#-introduction)
- [Prerequisites](#-prerequisites)
- [What to Learn](#-what-to-learn)
- [Web Application Security](#-web-application-security)
- [API Security](#-api-security)
- [Essential Bug Bounty Tools](#-essential-bug-bounty-tools)
- [Learning Resources](#-learning-resources)
- [Practice Platforms and Labs](#-practice-platforms-and-labs)
- [Bug Bounty Platforms](#-bug-bounty-platforms)
- [Vulnerability Databases](#-vulnerability-databases)
- [Bug Bounty Methodology](#-bug-bounty-methodology)
- [How to Write a Bug Bounty Report](#-how-to-write-a-bug-bounty-report)
- [30-Day Beginner Roadmap](#-30-day-beginner-roadmap)
- [Tips for Beginners](#-tips-for-beginners)
- [Legal and Ethical Guidelines](#-legal-and-ethical-guidelines)
- [Contributing](#-contributing)

---

# 🎯 Introduction

### What is a Security Vulnerability?

A security vulnerability is a weakness in software, hardware, or system design that can be exploited to compromise the confidentiality, integrity, or availability of a system.

Examples include:

- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Broken Access Control
- Server-Side Request Forgery (SSRF)
- Authentication Bypass
- Insecure Direct Object Reference (IDOR)
- Remote Code Execution (RCE)
- Security Misconfiguration

### What is Bug Bounty Hunting?

Bug bounty hunting is the process of identifying and responsibly reporting security vulnerabilities in websites, applications, APIs, and other digital systems through authorized security programs.

Organizations run bug bounty programs to encourage independent security researchers to discover vulnerabilities before malicious attackers exploit them.

### What are the Rewards?

Rewards depend on the vulnerability's severity, business impact, exploitability, and the organization's bounty policy.

Common rewards include:

- 💰 Monetary rewards
- 🏆 Hall of Fame recognition
- 🎁 Merchandise and gifts
- 📜 Certificates and recognition
- 💻 Premium subscriptions

Some programs offer rewards ranging from a few dollars to thousands of dollars or more.

**Remember:** Finding valid vulnerabilities requires patience, consistency, and practical experience. There is no guaranteed income in bug bounty hunting.

---

# 🧠 Prerequisites

Before jumping into vulnerability hunting, build a strong technical foundation.

You don't need to master everything before starting. Learn the fundamentals and improve through hands-on practice.

# 📖 What to Learn

## 1. Computer Fundamentals

Understand how computers and applications work.

Topics:

- Computer architecture
- CPU, RAM, and storage
- Processes and threads
- Memory management
- File systems
- Client-server architecture

Resources:

- [CompTIA A+](https://www.comptia.org/certifications/a)
- [Computer Fundamentals – TutorialsPoint](https://www.tutorialspoint.com/computer_fundamentals/index.htm)

## 2. Computer Networking

Networking is one of the most important foundations of cybersecurity.

Topics:

- OSI and TCP/IP models
- IP addresses and subnetting
- DNS
- HTTP and HTTPS
- TCP and UDP
- Ports and protocols
- Proxies
- Firewalls
- VPNs
- TLS/SSL

Resources:

- [Computer Networking – Cisco](https://www.netacad.com/)
- [Computer Networking Course – freeCodeCamp](https://www.youtube.com/watch?v=qiQR5rTSshw)
- [Cloudflare Learning Center](https://www.cloudflare.com/learning/)

## 3. Operating Systems

Learn how operating systems manage applications, users, processes, and permissions.

**Linux:**

- Linux file systems
- Users and permissions
- Processes and services
- Shell scripting
- Package management
- System administration

**Windows:**

- Windows architecture
- PowerShell
- CMD
- Windows services
- File permissions
- Event logs

Resources:

- [Linux Journey](https://linuxjourney.com/)
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/)
- [Microsoft Learn](https://learn.microsoft.com/)

## 4. Command Line

Learn to work efficiently with terminals.

**Linux:**
- `ls`, `cd`, `pwd`
- `cat`, `grep`, `find`
- `chmod`, `chown`
- `curl`, `wget`
- `ssh`, `netstat`
- `sudo`, `ps`

**Windows:**
- CMD
- PowerShell
- `ipconfig`
- `netstat`
- `ping`
- `tracert`
- `curl`

## 5. Programming and Scripting

Programming helps you understand application logic, identify vulnerabilities, and build your own security tools.

Recommended languages:

| Language | Why Learn It? |
|---|---|
| Python | Automation, scripting, security tools |
| JavaScript | DOM, XSS, browser security |
| SQL | Database queries and SQL injection |
| PHP | Understanding web application backends |
| C/C++ | Memory management and low-level security |
| Bash | Linux automation and scripting |

Useful resources:

- [Python – Official Tutorial](https://docs.python.org/3/tutorial/)
- [JavaScript – MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [SQLBolt](https://sqlbolt.com/)
- [freeCodeCamp](https://www.freecodecamp.org/)

---

# 🌐 Web Application Security

This should be your primary focus when starting web-based bug bounty hunting.

Understand how websites work internally, how authentication works, how data moves between frontend and backend, and how applications communicate with databases.

### Important Topics

- HTML, CSS, and JavaScript
- HTTP requests and responses
- HTTP headers and cookies
- Sessions and authentication
- Authorization and access control
- REST APIs
- JSON and XML
- CORS
- Same-Origin Policy
- JWT
- OAuth 2.0
- WebSockets
- File uploads
- Database interactions
- Business logic

### OWASP Top 10

Study the OWASP Top 10 to understand common web application security risks.

Official resource:

[OWASP Top 10](https://owasp.org/www-project-top-ten/)

Important vulnerability categories:

1. Broken Access Control
2. Security Misconfiguration
3. Software Supply Chain Failures
4. Cryptographic Failures
5. Injection
6. Insecure Design
7. Authentication Failures
8. Software or Data Integrity Failures
9. Security Logging and Alerting Failures
10. Mishandling of Exceptional Conditions

---

# 🔐 API Security

Modern applications heavily depend on APIs. Understanding API security can give you an advantage when hunting vulnerabilities.

Topics to learn:

- REST API architecture
- HTTP methods
- Authentication and authorization
- JWT vulnerabilities
- Broken Object Level Authorization (BOLA)
- Broken Function Level Authorization (BFLA)
- Mass Assignment
- Excessive Data Exposure
- Rate Limiting
- Improper API Authentication
- Input Validation
- Business Logic Vulnerabilities

Recommended resource:

[OWASP API Security Top 10](https://owasp.org/API-Security/)

**Practice idea:** Build a small Django REST Framework application with authentication, user profiles, employee records, and role-based permissions. Then test your own application for access control and API security weaknesses.

---

# 🛠️ Essential Bug Bounty Tools

Tools help security researchers analyze applications, inspect traffic, discover assets, and automate repetitive tasks.

## 1. Web Application Testing

| Tool | Purpose |
|---|---|
| [Burp Suite](https://portswigger.net/burp) | Intercept and analyze HTTP traffic |
| [OWASP ZAP](https://www.zaproxy.org/) | Web application security testing |
| [Caido](https://caido.io/) | Web traffic inspection and testing |
| [Postman](https://www.postman.com/) | API testing |
| [Insomnia](https://insomnia.rest/) | API development and testing |

## 2. Reconnaissance and Asset Discovery

| Tool | Purpose |
|---|---|
| [Subfinder](https://github.com/projectdiscovery/subfinder) | Subdomain discovery |
| [Amass](https://github.com/owasp-amass/amass) | Attack surface mapping |
| [httpx](https://github.com/projectdiscovery/httpx) | HTTP probing |
| [Katana](https://github.com/projectdiscovery/katana) | Web crawling |
| [Nmap](https://nmap.org/) | Network discovery and scanning |
| [Shodan](https://www.shodan.io/) | Internet-connected asset discovery |
| [Censys](https://search.censys.io/) | Internet asset search |

## 3. Vulnerability Testing

| Tool | Purpose |
|---|---|
| [Nuclei](https://github.com/projectdiscovery/nuclei) | Template-based vulnerability scanning |
| [SQLmap](https://sqlmap.org/) | SQL injection testing |
| [Nikto](https://github.com/sullo/nikto) | Web server security testing |
| [ffuf](https://github.com/ffuf/ffuf) | Web fuzzing |
| [Gobuster](https://github.com/OJ/gobuster) | Directory and DNS enumeration |

## 4. Useful Wordlists

- [SecLists](https://github.com/danielmiessler/SecLists)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [FuzzDB](https://github.com/fuzzdb-project/fuzzdb)

> Tools are only as effective as the person using them. Understand what a tool does, validate its findings manually, and never depend entirely on automated scanners.

---

# 📚 Learning Resources

## Books

1. [The Web Application Hacker's Handbook](https://www.wiley.com/en-us/The+Web+Application+Hacker%27s+Handbook%3A+Finding+and+Exploiting+Security+Flaws%2C+2nd+Edition-p-9781118026472)
2. [Real-World Bug Hunting](https://nostarch.com/bughunting)
3. [Bug Bounty Bootcamp](https://nostarch.com/bug-bounty-bootcamp)
4. [Hands-On Bug Hunting for Penetration Testers](https://www.packtpub.com/)
5. [The Hacker Playbook 3](https://www.hackerplaybook.com/)

## Writeups and Research

Reading other researchers' reports is one of the best ways to improve your methodology.

- [HackerOne Hacktivity](https://hackerone.com/hacktivity)
- [Bugcrowd CrowdStream](https://bugcrowd.com/crowdstream)
- [InfoSec Writeups](https://infosecwriteups.com/)
- [PortSwigger Research](https://portswigger.net/research)
- [Google VRP Writeups](https://github.com/xdavidhu/awesome-google-vrp-writeups)

## Blogs and Articles

- [PortSwigger Blog](https://portswigger.net/blog)
- [Intigriti Blog](https://blog.intigriti.com/)
- [Bugcrowd Blog](https://www.bugcrowd.com/blog/)
- [Hacking Articles](https://www.hackingarticles.in/)
- [Cloudflare Blog](https://blog.cloudflare.com/)
- [OWASP](https://owasp.org/)

## YouTube Channels

**English:**

- [InsiderPhD](https://www.youtube.com/@InsiderPhD)
- [STÖK](https://www.youtube.com/@STOKfredrik)
- [LiveOverflow](https://www.youtube.com/@LiveOverflow)
- [PwnFunction](https://www.youtube.com/@PwnFunction)
- [NahamSec](https://www.youtube.com/@NahamSec)
- [Bug Bounty Reports Explained](https://www.youtube.com/@BugBountyReportsExplained)
- [HackerOne](https://www.youtube.com/@HackerOne)

---

# 🧪 Practice Platforms and Labs

Theory alone is not enough. Spend as much time as possible practicing in intentionally vulnerable environments.

## Beginner-Friendly Platforms

| Platform | Description |
|---|---|
| [TryHackMe](https://tryhackme.com/) | Guided cybersecurity learning paths |
| [PicoCTF](https://picoctf.org/) | Beginner-friendly security challenges |
| [Hacker101](https://www.hacker101.com/) | Free web security training |
| [OverTheWire](https://overthewire.org/) | Linux and security challenges |
| [Hack The Box](https://www.hackthebox.com/) | Practical cybersecurity labs |

## Web Application Security Labs

**Highly recommended:**

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
- [DVWA](https://github.com/digininja/DVWA)
- [bWAPP](http://www.itsecgames.com/)
- [Google XSS Game](https://xss-game.appspot.com/)
- [PentesterLab](https://pentesterlab.com/)
- [CTFChallenge](https://ctfchallenge.co.uk/)

**My recommendation:** Start with PortSwigger Web Security Academy. It provides structured learning paths, explanations, and hands-on labs for real-world web vulnerabilities.

---

# 🏆 Bug Bounty Platforms

Once you understand the fundamentals and have practiced in labs, start exploring public and private bug bounty programs.

## Crowdsourced Bug Bounty Platforms

| Platform | Website |
|---|---|
| HackerOne | https://www.hackerone.com/ |
| Bugcrowd | https://www.bugcrowd.com/ |
| Intigriti | https://www.intigriti.com/ |
| YesWeHack | https://www.yeswehack.com/ |
| Open Bug Bounty | https://www.openbugbounty.org/ |

## Individual Security Programs

- [Google Vulnerability Reward Program](https://bughunters.google.com/)
- [Meta Bug Bounty](https://www.facebook.com/whitehat/)
- [Microsoft Security Response Center](https://msrc.microsoft.com/)
- [Apple Security Bounty](https://security.apple.com/bounty/)

Always read the program's scope, exclusions, testing requirements, and disclosure policies before starting.

---

# 🔎 Vulnerability Databases

Stay updated with publicly disclosed vulnerabilities, security advisories, and new attack techniques.

| Resource | Purpose |
|---|---|
| [NIST NVD](https://nvd.nist.gov/) | National Vulnerability Database |
| [MITRE CVE](https://www.cve.org/) | Common Vulnerabilities and Exposures |
| [GitHub Advisory Database](https://github.com/advisories) | Software security advisories |
| [OSV.dev](https://osv.dev/) | Open-source vulnerability database |
| [Snyk Vulnerability Database](https://security.snyk.io/) | Package vulnerability research |
| [Exploit-DB](https://www.exploit-db.com/) | Public exploit database |
| [InTheWild](https://inthewild.io/) | Exploited vulnerability tracking |
| [Microsoft Security Response Center](https://msrc.microsoft.com/update-guide) | Microsoft security advisories |

---

# 🔍 Bug Bounty Methodology

Develop your own methodology instead of blindly following tools and automated scripts.

A basic workflow:

### 1. Program Selection

- Choose a beginner-friendly program.
- Read the program policy.
- Understand in-scope and out-of-scope assets.
- Check prohibited testing techniques.

### 2. Reconnaissance

- Identify authorized domains and subdomains.
- Understand the application's functionality.
- Discover publicly available endpoints.
- Identify technologies and frameworks.
- Map the application's attack surface.

### 3. Application Mapping

- Explore registration and login.
- Analyze user roles and permissions.
- Understand API endpoints.
- Inspect parameters and HTTP requests.
- Identify sensitive functionality.

### 4. Vulnerability Testing

Focus on understanding:

- Broken Access Control
- IDOR / BOLA
- Authentication vulnerabilities
- SQL Injection
- Cross-Site Scripting
- SSRF
- File Upload vulnerabilities
- Business Logic vulnerabilities
- Security Misconfiguration

### 5. Validation

- Reproduce the issue.
- Confirm the actual security impact.
- Avoid unnecessary data access.
- Ensure the finding is within scope.
- Check for duplicate or known issues.

### 6. Reporting

- Prepare clear reproduction steps.
- Explain the business impact.
- Attach screenshots or a safe proof of concept.
- Submit through the official reporting channel.

---

# 📝 How to Write a Bug Bounty Report

A good vulnerability report should be clear, technically accurate, reproducible, and focused on real-world impact.

Use the following structure:

## 1. Title

Write a short and descriptive title explaining the vulnerability and its impact.

Example:

`[IDOR] Unauthorized Access to Other Users' Private Profile Information`

## 2. Description

Explain:

- What the vulnerability is.
- Where it exists.
- How it occurs.
- Which functionality is affected.

## 3. Steps to Reproduce

Provide clear, numbered steps.

Example:

1. Log in using your own test account.
2. Navigate to the profile section.
3. Inspect the relevant API request.
4. Identify the object ID in the request.
5. Test access using a second account you control.
6. Verify whether unauthorized information is exposed.

## 4. Proof of Concept (PoC)

Provide supporting evidence:

- Screenshots
- HTTP request and response
- Screen recording
- Relevant application behavior

Use only data and accounts you are authorized to test.

## 5. Impact

Explain the actual security consequences.

Consider:

- Confidentiality impact
- Integrity impact
- Availability impact
- Affected users
- Business consequences
- Practical exploitation scenarios

## 6. Suggested Remediation

Where possible, suggest a practical solution.

For example:

- Enforce server-side authorization.
- Validate object ownership.
- Apply role-based access control.
- Validate and sanitize user input.
- Implement appropriate rate limits.

---

# 📅 30-Day Beginner Roadmap

A practical starting plan to build your foundation.

| Days | Learning Focus | Goal |
|---|---|---|
| 1–3 | Computer and networking fundamentals | Understand how systems communicate |
| 4–6 | Linux and command line | Become comfortable with terminals |
| 7–9 | HTTP, HTTPS, DNS, cookies | Understand web communication |
| 10–12 | HTML, JavaScript, SQL | Understand web application components |
| 13–16 | Burp Suite and HTTP testing | Inspect and modify web requests in labs |
| 17–21 | OWASP Top 10 | Learn common vulnerabilities |
| 22–25 | PortSwigger Academy | Solve practical security labs |
| 26–28 | API Security | Understand API vulnerabilities |
| 29–30 | Reporting and methodology | Write your first practice report |

**After 30 days:** Continue solving advanced labs, reading disclosed reports, and building your own testing methodology.

This is a starting roadmap, not a guarantee that you will be ready to earn bug bounty rewards within 30 days.

---

# 💡 Tips for Beginners

1. **Be consistent:** Spend time learning and practicing every day, even if it is only one hour.

2. **Focus on fundamentals:** Understanding HTTP, networking, programming, and application architecture is more valuable than memorizing payloads.

3. **Don't depend entirely on automation:** Tools can identify potential issues, but manual testing and understanding business logic are essential.

4. **Read vulnerability reports:** Learn how experienced researchers discover, validate, and report security issues.

5. **Build your own methodology:** Understand the application before testing it. Every application has different functionality and potential weaknesses.

6. **Think beyond common vulnerabilities:** Explore authorization problems, multi-step workflows, business logic, and API security.

7. **Document everything:** Maintain notes about what you learn, useful commands, testing approaches, and interesting findings.

8. **Don't chase money initially:** Treat bug bounty hunting as a way to develop practical cybersecurity skills. Rewards should be a bonus, not an expectation.

9. **Avoid duplicate reports:** Research known findings and understand the program's scope before submitting.

10. **Stay connected:** Follow security researchers, participate in communities, attend cybersecurity events, and share knowledge.

---

# ⚖️ Legal and Ethical Guidelines

Ethical hacking requires permission and responsibility.

Always follow these rules:

- Only test applications and systems where you have explicit authorization.
- Never test out-of-scope assets.
- Do not access, modify, or download other people's private information.
- Avoid destructive testing and denial-of-service attacks.
- Do not perform social engineering unless explicitly authorized.
- Follow responsible disclosure guidelines.
- Respect program policies and applicable laws.

**Remember:** Unauthorized testing can have legal consequences, even if your intention is to help.

---

# 🤝 Contributing

This repository is open to contributions from everyone interested in cybersecurity and ethical hacking.

You can contribute by:

- Adding useful learning resources.
- Sharing educational writeups.
- Improving existing documentation.
- Adding practical lab exercises.
- Suggesting useful security tools.
- Correcting outdated information.
- Sharing beginner-friendly learning paths.

### How to Contribute

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.
5. Explain what you added or improved.

Please ensure all contributions are educational, accurate, and legally appropriate.

---

# ⭐ Support This Repository

If you find this roadmap useful:

- Give this repository a ⭐ Star.
- Fork it and share it with others.
- Contribute useful resources.
- Share your learning experience.
- Help other beginners get started.

Every contribution helps make cybersecurity learning more accessible.

---

<p align="center">
  <b>Keep Learning. Keep Practicing. Keep Exploring.</b>
  <br/>
  <br/>
  Made with ❤️ by <b>Asim Sapkota</b>
  <br/>
  <i>Learning Cybersecurity, One Vulnerability at a Time.</i>
</p>
