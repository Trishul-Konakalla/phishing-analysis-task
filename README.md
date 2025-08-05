# 🛡️ Phishing Email Analysis using Kali Linux

This project documents a complete phishing investigation task performed using **Kali Linux**.  
The objective was to analyze a suspicious email header, trace its origin, verify its authenticity, and identify any phishing characteristics using Linux-based tools.

---

## 🎯 Task Objective

To analyze a suspicious email using **Kali Linux tools** and determine whether it is a **phishing email or a legitimate one** based on technical indicators.

---

## 🖥️ What I Did (Step-by-Step in Kali Linux)

1. **Created a working directory** to manage all phishing-related files.
2. **Extracted the full email header** and saved it as `email_header.txt`.
3. **Used `whois` command** to trace:
   - The IP address found in the email header (`103.52.182.47`)
   - The sender’s domain (`nopaperforms.info`)
4. **Captured screenshots** of the WHOIS results using `gnome-screenshot` (or `scrot`) and saved them as:
   - `whois_result.png`
   - `whois_nopaperforms.png`
5. **Analyzed SPF, DKIM, and Return-Path headers** to identify spoofing or email tampering.
6. **Wrote a detailed report** in `phishing_analysis_report.txt` explaining:
   - Email origin and path
   - IP legitimacy
   - Domain registration information
   - Authentication result summary
7. **Organized and uploaded** all findings and screenshots to GitHub.

---

## 🧠 What I Learned

✔ How to analyze email headers in depth  
✔ How to investigate sender IPs and domains using Linux terminal tools  
✔ How to verify SPF/DKIM authentication results  
✔ How to distinguish legitimate marketing emails from phishing attempts  
✔ How to report cybersecurity investigations clearly and professionally

---

## 🛠️ Tools Used (on Kali Linux)

| Tool | Use Case |
|------|----------|
| `whois` | IP and domain investigation |
| `gnome-screenshot` / `scrot` | Terminal-based screenshot capture |
| `nano` | File editing and report writing |
| `Kali Linux` | OS environment for penetration testing and analysis |

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `email_header.txt` | The full raw header of the suspicious email |
| `whois_result.png` | Screenshot of IP WHOIS result for 103.52.182.47 |
| `whois_nopaperforms.png` | Screenshot of domain WHOIS result for nopaperforms.info |
| `phishing_analysis_report.txt` | Full written report of the analysis task |
| `whois_analysis.txt` *(optional)* | Additional analysis of WHOIS findings |

---

## ✅ Conclusion of Investigation

> After deep analysis using Kali Linux, the email was determined to be **legitimate**.  
> It was sent by **Woxsen University** using a verified third-party marketing service (**NetcoreCloud**), with SPF and DKIM authentication successfully verified.

---

## ✍️ Author

**Konakalla Trishul**  
Cybersecurity Intern  
📆 Task Date: **5th August 2025**  
🖥️ Performed on: **Kali Linux**  
🔗 [GitHub Profile](https://github.com/your-username)

---
