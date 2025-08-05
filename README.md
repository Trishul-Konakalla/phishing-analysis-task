# 🛡️ Phishing Email Analysis using Kali Linux

This project contains the full analysis of a suspicious email to determine if it was a **phishing attack or a legitimate message**, using various investigation techniques on **Kali Linux**.

---

## 🎯 Objective

To perform technical analysis of a suspicious email by extracting and examining its header, sender IP, and domain using Kali Linux tools, and conclude whether it is a phishing attempt or not.

---

## 🖥️ Steps Performed in Kali Linux

✅ **1. Created a working folder** in `/home/kali/phishing-task`  
✅ **2. Saved the full email header** from Gmail into `email_header.txt`  
✅ **3. Ran WHOIS on sender IP `103.52.182.47`:**

whois 103.52.182.47
📌 Result: IP belongs to Netcore Solutions Pvt Ltd, a legitimate Indian email marketing company.

✅ 4. Ran WHOIS on sender domain nopaperforms.info:

whois nopaperforms.info
📌 Result: Domain registered via GoDaddy in 2015, protected via Domains By Proxy, and used AWS + Cloudflare DNS. Not suspicious by itself.

✅ 5. Analyzed header info:

SPF: ✅ PASS

DKIM: ✅ PASS

Return-Path and From: mismatch: ⚠️ Possible red flag

ARC, DKIM, SPF headers confirmed authenticity

✅ 6. Wrote a detailed report in phishing_analysis_report.txt
✅ 7. Took screenshots of both WHOIS commands as proof
✅ **8. Uploaded all findings to GitHub

🧠 What I Learned
✔ How to read and analyze full email headers
✔ How to trace sender identity using WHOIS
✔ How to interpret SPF, DKIM, ARC headers
✔ How to detect spoofing and phishing indicators
✔ How to report findings with professionalism
✔ How to work in Kali Linux for email forensics

🛠️ Tools Used
Tool	Description
whois	Investigate sender's IP and domain ownership
gnome-screenshot / scrot	Capture terminal output as proof
nano	Report writing in terminal
Kali Linux	Linux distro used for cybersecurity analysis

📁 Files in This Repository
File Name	Purpose
email_header.txt	Raw header of the suspicious email
whois_result.png	Screenshot of WHOIS for IP 103.52.182.47
whois_nopaperforms.png	Screenshot of WHOIS for domain nopaperforms.info
phishing_analysis_report.txt	Full technical analysis report
whois_analysis.txt (optional)	Text summary of WHOIS findings

✅ Final Conclusion
After full investigation using Kali Linux:

🧪 The email is not a phishing attempt.
It is a legitimate marketing message from Woxsen University, sent via NetcoreCloud (delivery platform) using authenticated headers.
SPF and DKIM authentication passed, and WHOIS data confirmed sender IP and domain legitimacy.

✍️ Author
Konakalla Trishul
Cybersecurity Intern
📅 Date of Task: 5th August 2025
💻 Environment: Kali Linux
🔗 GitHub Profile
