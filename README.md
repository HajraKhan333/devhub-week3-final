# devhub-week3-final
Week 3 – Final Project for my Cybersecurity Internship at DevelopersHub. Includes penetration testing, logging with Winston, and a security checklist.

## 📌 Overview
This is the final deliverable for Week 3 of my Cybersecurity Internship at **DevelopersHub**.  
In this week, I performed penetration testing, added logging with Winston, and created a security checklist.  
This completes the cycle of assessment (Week 1), fixes (Week 2), and final validation (Week 3).  

## 🛠️ Week 3 Work

### 🔹 Penetration Testing
- **Nmap Scan**: Confirmed only expected port (3000) open.  
- **XSS Retest**: `<script>alert(1)</script>` → blocked by input validation.  
- **SQL Injection Retest**: `' OR 1=1--` → no longer bypasses login due to bcrypt & validation.  

### 🔹 Logging with Winston
- Implemented logging for user signup and login.  
- Logs are visible both in console and saved into `security.log`.  

### 🔹 Security Checklist
See [checklist.md](./checklist.md) for final security checklist.


## 📂 Deliverables
- 📄 [Week 3 Report (PDF)](./Week3.pdf)  
- 🎥 [Final Video Walkthrough](https://drive.google.com/file/d/1jXfXJ8EdBY0-m-7Z6XTPsd-ymErAt9Qp/view?usp=sharing)  
- 📜 [Checklist](./checklist.md)  
- 💻 Source code (this repo)  


## ✅ Summary
- **Week 1:** Security Assessment (XSS, SQLi, misconfigurations)  
- **Week 2:** Fixed vulnerabilities with validator, bcrypt, JWT, Helmet  
- **Week 3:** Verified with Penetration Testing, added logging, and finalized checklist  

This concludes my internship tasks for DevelopersHub. 🚀
