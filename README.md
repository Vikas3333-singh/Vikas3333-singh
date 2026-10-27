# Hi, I'm Vikas Singh 👋
### End User Support & Workplace Specialist | 11+ Years Experience
**L1/L2 Deskside & VIP Support • Windows & macOS • M365 • Entra ID • Intune & Autopilot • ServiceNow (ITIL 4) • 95%+ SLA**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-singh-816657ab)
[![Email](https://img.shields.io/badge/Email-Get_In_Touch-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vikaskumarsingh333@gmail.com)
[![Portfolio](https://img.shields.io/badge/Live_Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://vikas3333-singh.github.io/vikas-singh.github.io/)
📍 **Gurugram, Haryana, India**  
🎯 **Looking for:** Workplace Services • Deskside & VIP Support Lead • Endpoint Operations
---
## ☕ A Quick Intro
I’ve spent the last **11+ years working in the trenches of enterprise IT support**. 
From fixing broken laptop screens and resolving Wi-Fi drops to managing 500+ secure endpoints for consultants at **Boston Consulting Group (BCG)**, my philosophy has always been simple: **keep people working, keep systems secure, and automate the boring, repetitive tasks.**
I don't just close tickets; when I see my team doing the exact same manual task 10 times a day, I open an editor and write a Python script or PowerShell workflow to automate it.
---
## 📊 Real Numbers from the Field
| Area | The Old Manual Way | How I Solved It | The Real Impact |
| :--- | :--- | :--- | :--- |
| **Lenovo Warranty Claims** | 15–20 mins per laptop on web portal | Wrote a Python + Selenium tool (`TicketForge`) | **Cut to <15 seconds per unit** (batch done in under 2 mins) |
| **Routine Laptop Tune-ups** | 35–45 mins of manual checks | Built a 1-click cross-platform utility (`AITU`) | **Down to 4.5 minutes** with zero guesswork |
| **New Laptop Prep** | 2.5 hours of manual installs | Deployed Intune & Windows Autopilot | **<20 mins of engineer touch-time** |
| **Security Patching** | Patch levels slipping each month | Standardized MECM & Intune update rings | **Maintained 97%+ patch compliance** across 500+ machines |
| **Asset Audits** | 4 hours every week matching spreadsheets | Built a browser-based asset tracker dashboard | **Reduced audit time to under 20 minutes** |
| **VIP Executive Support** | Panic when tech fails in leadership meetings | Pre-flight testing & dedicated VIP room checks | **100% uptime across 30+ major Partner events** |
---
## 🛠️ What I Work With Daily
- **Endpoint Management:** Microsoft Intune, MECM / SCCM, Jamf Pro (macOS), Windows Autopilot
- **Deskside & Break-Fix:** Laptop teardowns, RAM/SSD upgrades, battery/display replacement, dock troubleshooting
- **Identity & Cloud:** Microsoft Entra ID (Azure AD), Microsoft 365 Admin Centre, MFA, SSO, Dynamic Groups
- **Automation & Scripting:** Python (Selenium, openpyxl), PowerShell, Bash, Batch
- **Ticketing & Process:** ServiceNow (Incident, Request, Change, Asset), ITIL 4 Foundation
- **Operating Systems:** Windows 10/11 Enterprise, macOS (Ventura, Sonoma, Sequoia), iOS/Android
- **Office Infrastructure:** Network printers, conference room AV (Teams Rooms / Zoom), LAN, Wi-Fi, VPN
---
## 💡 Projects I Built to Solve Real Daily Headaches
### 1. [Lenovo-E-Ticket-Automation (TicketForge)](https://github.com/Vikas3333-singh/Lenovo-E-Ticket-Automation/tree/main)
*A tool to stop wasting hours on the Lenovo warranty portal.*
- **The Headache:** When laptops broke down with swollen batteries, bad motherboards, or broken screens, I had to open Lenovo's support portal and fill out the same 15 form fields over and over for every single laptop. For 8 to 10 machines, it ate 2.5 to 3 hours of my morning.
- **What I Did:** I wrote a Python script using headless Selenium and `openpyxl`. It takes our Excel queue of broken laptops, logs into the Lenovo portal automatically, submits the claims, captures the case confirmation numbers, and writes them straight back into the spreadsheet.
- **The Result:** Submitting an 8-device batch went from **almost 3 hours to 1 minute and 42 seconds**. Vendor engineers were dispatched the same day, and our team got hours back to focus on real user issues.
---
### 2. [Advanced IT Troubleshooting Utility (AITU)](https://github.com/Vikas3333-singh)
*One command to clean, repair, and diagnose sluggish laptops.*
- **The Headache:** Every time a user reported a slow laptop or a corrupted Office app, technicians were manually running SFC, DISM, clearing app caches, and digging through services one by one (35–45 minutes per call).
- **What I Did:** I created two clean scripts—`windows_maintenance_final.bat` for Windows and `maintenance.sh` for macOS. They include silent CLI flags for Intune deployment, a non-destructive dry-run mode, and a simple menu where techs can type an issue in plain English to trigger the right fix.
- **The Result:** Routine health cleanups dropped from **40 minutes down to 4.5 minutes**, and L1 escalations dropped by 74%.
---
### 3. Hands-Off Laptop Deployment (Windows Autopilot + Intune)
*Getting new hires up and running without touching their machines.*
- **The Headache:** In our hybrid setup, shipping laptops back to the office just to image them was slow, expensive, and tied up support staff for hours on the phone with new joiners.
- **What I Did:** I set up Windows Autopilot linked with Microsoft Intune. We drop-ship the laptop straight from the vendor. The user opens the lid, connects to home Wi-Fi, logs in with their work email, and Intune automatically installs their apps, turns on BitLocker, and applies security policies.
- **The Result:** Cut technician hands-on time from 2.5 hours down to practically zero, giving new hires a smooth Day-1 experience.
---
### 4. [IT Asset Tracker & Hardware Dashboard](https://github.com/Vikas3333-singh/it-asset-tracker)
*Replacing messy spreadsheets with a visual inventory view.*
- **The Headache:** Keeping track of 500+ laptops across office and remote staff meant digging through messy Excel sheets every Friday just to see which devices were out of warranty.
- **What I Did:** Built a lightweight browser dashboard using HTML, CSS, JavaScript, and Chart.js to give the IT team a clear, visual breakdown of hardware status, warranty expiration dates, and assigned users.
- **The Result:** Weekly asset reporting dropped from **4 hours of manual cross-checking to under 20 minutes**.
---
## 💼 Work Experience
### **Senior Desktop Support Engineer**
**Femmella Fashions Pvt. Ltd.** | *Gurugram, Haryana*  
*Jan 2026 – Present*
- **Hands-on Hardware Support:** Run daily deskside support for 150+ corporate and warehouse users, handling hardware upgrades (RAM/SSD), battery replacements, Windows crashes, and Outlook/M365 issues.
- **Built TicketForge:** Got tired of manual data entry on the Lenovo warranty portal, so I coded an automated Python/Selenium tool that submits batch warranty claims directly from an Excel list in under 2 minutes.
- **Onboarding & Offboarding:** Handle complete machine imaging, domain joins, software profiles, and handovers for new joiners, along with secure asset recovery when employees exit.
- **Office IT & Printers:** Keep the office running smoothly—managing network printers, barcode label printers, conference room AV, and Wi-Fi access points.
---
### **System Analyst (End User & Workplace Services)**
**Client: Boston Consulting Group (BCG)** — via Konverge Technologies | *Gurugram, Haryana*  
*Aug 2022 – Jan 2026*
- **Fleet Health (500+ Endpoints):** Managed mixed Windows, macOS, and mobile fleets using Intune, MECM, Jamf Pro, and Autopilot. Kept fleet patch compliance consistently above 97%.
- **VIP White-Glove Support:** Dedicated point of contact for Partners, Managing Directors, and Practice Leaders. Provided calm, zero-downtime deskside and AV support for 30+ high-stakes leadership meetings and townhalls.
- **Identity & Access:** Handled day-to-day Entra ID (Azure AD) tasks, Conditional Access rules, and MFA rollouts with a strict zero-trust approach.
- **Service Delivery:** Kept a **95.4% SLA adherence** on ServiceNow tickets by creating clear diagnostic playbooks and root-cause fixes.
- **Smart Support:** Wrote PowerShell scripts that automated routine user fixes, deflecting 30% of repetitive L1 tickets.
---
### **Senior Technical Support Engineer**
**Puthur Infotech Pvt. Ltd.** | *Patna, Bihar*  
*Mar 2018 – Aug 2022*
- **Windows 10 Migration:** Led the migration of 180+ mission-critical office workstations from Windows 7 to Windows 10 using SCCM and PXE boot within a tight 6-week window.
- **Team Guidance:** Trained and mentored 6 junior support techs on ITIL ticketing standards and structured troubleshooting, boosting our First Contact Resolution (FCR) by 22%.
- **Asset Control:** Managed the physical IT inventory of 200+ machines with 96% audit accuracy.
---
### **Technical Support Engineer**
**Client: Rural Electrification Corporation (REC)** — via Atlanta Systems | *New Delhi*  
*May 2015 – Mar 2018*
- **Multi-Branch Support:** Handled Tier 1/2 support for 200+ users across the REC Headquarters and 15+ remote regional branch offices.
- **Network & Email Stability:** Resolved VPN drops, LAN issues, and Exchange mailbox issues under strict government compliance rules with an average resolution time under 4 hours.
---
## 📜 Certifications
- **ITIL 4 Foundation in IT Service Management** — PeopleCert / Simplilearn
- **macOS Support & Administration Essentials** — Apple / LinkedIn Learning
- **Microsoft Copilot & AI Productivity Essentials** — Microsoft Press
- **Python for IT Operations & Automation** — Google / Coursera
- **Generative AI: Enterprise Prompt Engineering** — LinkedIn Learning
---
## 📬 Let's Connect
- **LinkedIn:** [linkedin.com/in/vikas-singh-816657ab](https://www.linkedin.com/in/vikas-singh-816657ab)
- **Email:** [vikaskumarsingh333@gmail.com](mailto:vikaskumarsingh333@gmail.com)
- **Portfolio:** [vikas3333-singh.github.io](https://vikas3333-singh.github.io/vikas-singh.github.io/)
*If you're looking for someone who can manage end-user technology, support executives without panic, and build practical automations that save real time—let's talk.*
