# 🛡️ TryHackMe - Offensive Security Intro (Module 1)

## 🧠 Task 1: Think Like a Hacker

### Key Concept
**Offensive Security** focuses on thinking like an attacker to identify vulnerabilities before malicious hackers can exploit them.

It is a fundamental concept in **ethical hacking**, where security professionals simulate real-world attacks in a legal and controlled environment.

### What I Learned
- The importance of adopting an attacker’s mindset
- The role of offensive security in protecting systems
- Ethical hacking must always be authorized and legal

---

## 🛡️ Task 2: Starting the Lab

### Environment
- A **virtual desktop** is used to simulate a real system
- Interaction with a web application: **FakeBank**

### What I Learned
- How cybersecurity labs simulate real-world environments
- Basic interaction with a web-based system
- The importance of exploring applications to understand their structure

---

## 🔎 Task 3: Find Hidden Pages

### Key Concept
Web applications may contain **hidden or unlinked pages**, which can represent security vulnerabilities if exposed.

### Tool Used
- **dirb**: a directory brute-forcing tool used to discover hidden web pages

### Command
```bash
dirb http://fakebank.thm
```

### What I Learned
- How attackers discover hidden endpoints in web applications
- The role of brute-force tools in reconnaissance
- Why improperly secured directories can lead to vulnerabilities

---

## 💣 Task 4: Attack the Admin Page

### Key Concept
Hidden administrative panels can allow unauthorized users to perform critical actions if not properly secured.

### What I Learned
- How access to hidden pages can lead to privilege abuse
- The risks of insecure web application design
- How small vulnerabilities can escalate into serious security issues

---

## 🧠 Module Summary

- Offensive Security involves simulating attacks to identify weaknesses
- Web applications often expose vulnerabilities through:
  - hidden directories
  - poor access controls
- Tools like **dirb** are used during the reconnaissance phase
- Gaining unauthorized access can compromise critical system functions

---

## 🚀 Key Takeaways

- Thinking like an attacker is essential in cybersecurity
- Reconnaissance is a crucial step in any attack
- Misconfigured systems are a common source of vulnerabilities
- Practical labs are key to understanding real-world security concepts