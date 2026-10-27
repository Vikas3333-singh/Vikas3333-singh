# Hi, I'm Vikas Singh 👋
### Senior End User Support & Workplace Technology Specialist | 11+ Years Experience
**L1/L2 Deskside & VIP Support • Windows & macOS • Microsoft 365 • Entra ID • Intune & Autopilot • ServiceNow (ITIL 4) • 95%+ SLA**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-singh-816657ab)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vikaskumarsingh333@gmail.com)
[![Portfolio](https://img.shields.io/badge/Executive_Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vikas3333-singh.github.io/vikas-singh.github.io/)
📍 **Gurugram, Haryana, India** | 🎯 **Focus:** Senior Workplace Services • VIP Deskside Operations • Enterprise IT Automation
> *"Over 11+ years of proven expertise managing enterprise end-user computing (EUS), delivering white-glove VIP support for tier-1 management consulting environments (including Boston Consulting Group), and engineering custom Python/PowerShell automation to eliminate operational support bottlenecks."*
---
## Executive Career Snapshot (Real Operational Impact)
| Operational Domain | Legacy Baseline (Manual) | Optimized (Automated) | Strategic Business Impact |
| :--- | :--- | :--- | :--- |
| **Lenovo Warranty E-Ticketing** | 15–20 mins per claim | **<15 seconds per unit** | 90% reduction in vendor dispatch logging time via Python automation |
| **Endpoint Diagnostics MTTR** | 35–45 mins per laptop | **4.5 mins automated run** | 88.7% MTTR cut via cross-platform troubleshooting utility |
| **Cloud Device Provisioning** | Manual hands-on setup | **Unattended Cloud Staging** | 80% engineer touch-time saved via Intune & Windows Autopilot |
| **Fleet Patch Compliance** | 82%–88% (fluctuating) | **97%+ consistent** | Zero critical CVE vulnerabilities across 500+ heterogeneous devices |
| **IT Asset Reconciliation** | 4 hours/week manual Excel | **<20 minutes weekly** | 90% time saved with real-time browser-based asset lifecycle tracking |
| **Executive / VIP Meetings** | Occasional AV/tech delays | **100% Zero-Downtime** | White-glove IT support for 30+ Partner/Director townhalls & conferences |
---
## Core Technical Competencies

┌─────────────────────────────────┬─────────────────────────────────────────────────────────┐
│ Domain                          │ Enterprise Technology Stack                             │
├─────────────────────────────────┼─────────────────────────────────────────────────────────┤
│ Endpoint Management (MDM/MAM)   │ Microsoft Intune, MECM / SCCM, Jamf Pro, Windows Autopilot │
│ Automation & Software Dev       │ Python 3.x (Selenium, openpyxl), PowerShell, Bash, Batch │
│ Vendor Hardware & RMA Lifecycle │ Lenovo Commercial Support Portal, Apple Premier Support │
│ Identity & Access (IAM)         │ Microsoft Entra ID (Azure AD), M365 Admin, SSO, MFA, RBAC│
│ Operating Systems & Platforms   │ Windows 10/11 Enterprise, macOS (Ventura–Sequoia), iOS  │
│ ITSM & Frameworks               │ ServiceNow (Incident/Change/Problem/Asset), ITIL 4      │
│ Executive / Deskside Support    │ VIP White-Glove Support, Townhall AV, Teams Rooms / Zoom │
│ Infrastructure & Networking     │ TCP/IP, DNS, DHCP, GlobalProtect / Cisco AnyConnect VPN  │
└─────────────────────────────────┴─────────────────────────────────────────────────────────┘

---
## 🏆 Featured Engineering Projects
### 1. [Lenovo-E-Ticket-Automation (TicketForge)](https://github.com/Vikas3333-singh/Lenovo-E-Ticket-Automation/tree/main)
*Production-Grade Robotic Process Automation (RPA) for Enterprise Hardware Warranty Claims*
* **The Problem (Kya problem thi):** In enterprise environments, handling hardware failures (motherboard, display flickering, battery swelling, keyboard replacement) required support engineers to manually log into the Lenovo enterprise portal, fill 15+ repetitive form fields per device, wait for confirmation, and copy case IDs back into tracking spreadsheets. For 8–10 broken machines, this wasted 2.5 to 3 hours with constant human copy-paste mistakes.
* **The Action (Maine kya kiya):**
  * Engineered **TicketForge** using **Python 3.11, Selenium WebDriver (Headless mode)**, and **openpyxl** for batch processing.
  * Built dual execution workflows: single-device rapid command line execution or full automated batch submission directly from an Excel hardware queue manifest.
  * Implemented automated session authentication, multi-field payload injection, dynamic Lenovo Case ID scraping, and real-time bidirectional status sync back into Excel.
  * Added robust exception handling with automated retries for portal timeouts.
* **The Output (Kya result aaya):**
  * Submitting an 8-device hardware warranty batch was reduced from **~2.5 hours down to 1 minute 42 seconds**.
  * Achieved 100% submission accuracy with zero manual data entry errors.
* **The Business Benefit (Output se kya fayda mila):**
  * **Accelerated Vendor TAT:** Vendor dispatches and technician visits initiated the same business day instead of being delayed by manual admin work.
  * **Zero Missed Warranties:** Full audit visibility preventing devices from sitting untracked in storage rooms until warranty expiration.
  * **Reclaimed Engineering Capacity:** Reclaimed 4+ hours weekly per support technician, redirecting time to high-priority user tickets.
---
### 2. [Advanced IT Troubleshooting Utility (AITU)](https://github.com/Vikas3333-singh)
*Cross-Platform Automated Diagnostic & Maintenance Engine for Windows & macOS*
* **The Problem (Kya problem thi):** Support engineers spent 35–45 minutes manually cleaning caches, running SFC/DISM repairs, and checking hardware on degraded endpoints. No silent MDM push was possible, creating ticket backlogs.
* **The Action (Maine kya kiya):** Engineered a native dual-OS automation suite (`maintenance.sh` & `windows_maintenance_final.bat`) featuring 15 silent CLI switches for Intune/SCCM, atomic PID locking, non-destructive `--dry-run` modes, and a conversational issue-routing triage engine.
* **The Output (Kya result aaya):** Maintenance turnaround time dropped from **40 minutes to under 4.5 minutes** with automated 90-day JSON health telemetry.
* **The Business Benefit (Output se kya fayda mila):** **88.7% MTTR reduction**, 74% reduction in L2 escalations, and zero-touch background execution without disturbing business meetings.
---
### 3. Modern Workplace Cloud Provisioning (Windows Autopilot & Intune)
*Zero-Touch Endpoint Staging & Application Baselines*
* **The Problem (Kya problem thi):** Imaging remote and hybrid consultants' laptops required physical bench staging, lengthy manual software installations, and physical shipping back and forth from the central office.
* **The Action (Maine kya kiya):** Deployed **Windows Autopilot (User-Driven Entra ID Join)** integrated with Microsoft Intune. Configured dynamic device grouping, automated BitLocker enforcement, compliance policies, and mandatory M365 app packages.
* **The Output (Kya result aaya):** Enabled vendor-to-user drop-shipping; laptops automatically configure standard operating environments (SOE) unattended over Wi-Fi upon initial user login.
* **The Business Benefit (Output se kya fayda mila):** Eliminated technician manual imaging effort, ensured 100% corporate security policy compliance on Day 1, and eliminated double-handling shipping expenses.
---
### 4. [IT Asset Tracker & Hardware Lifecycle Dashboard](https://github.com/Vikas3333-singh/it-asset-tracker)
*Real-Time Enterprise Asset Governance & Compliance Platform*
* **The Problem (Kya problem thi):** Reconciling physical laptop inventory across remote and on-premise staff required 4 hours every week of manual Excel cross-matching, causing inventory leakage and untracked depreciation.
* **The Action (Maine kya kiya):** Built a web-based ITAM dashboard utilizing JavaScript, Chart.js, and automated log parsers to track lifecycle status, assigned consultants, warranty expiry, and device health.
* **The Output (Kya result aaya):** Weekly audit time decreased from **4 hours/week down to under 20 minutes** with live visualization.
* **The Business Benefit (Output se kya fayda mila):** Eliminated ghost assets, achieved **99%+ audit compliance**, and prevented costly software license overages.
---
## 💼 Professional Experience (11+ Years)
### **Senior IT Systems Specialist**
**Femmella Fashion**  
*Gurugram, Haryana | Jan 2026 – Present*
* **EUC & IAM Architecture:** Lead end-user computing operations and identity access governance (Joiner/Mover/Leaver) across enterprise systems.
* **Process Automation:** Architected and deployed **TicketForge (Lenovo E-Ticket Automation)**, eliminating manual vendor warranty ticket submission and reducing tracking lag to zero.
* **Compliance & Hardware Lifecycle:** Managing hardware refresh cycles, warranty renewals, and enterprise endpoint compliance.
---
### **System Analyst (End User & Workplace Services)**
**Client:** Boston Consulting Group (BCG) — via Konverge Technologies  
*Gurugram, Haryana | Aug 2022 – Jan 2026*
* **Enterprise Fleet Governance:** Administered 500+ endpoints (Windows, macOS, Mobile) across BCG offices ensuring **97%+ patch compliance** against critical CVE vulnerabilities.
* **VIP White-Glove Support:** Dedicated deskside support lead for Partners, Managing Directors, and Practice Area Leaders; provided zero-downtime support for 30+ critical tier-1 meetings and executive townhalls.
* **Modern IAM Operations:** Managed Entra ID (Azure AD) lifecycle, Conditional Access policies, automated group memberships, and MFA enforcement adhering strictly to global zero-trust principles.
* **SLA Leadership:** Maintained a **95.4% SLA compliance rate** in ServiceNow across P1–P5 incidents by developing structured root-cause analysis (RCA) and standard operating procedures (SOPs).
* **Automation:** Authored PowerShell and shell remediation tools that deflected **30% of repetitive L1 tickets**, empowering end users with self-healing tools.
---
### **Senior Technical Support Engineer**
**Puthur Infotech Pvt. Ltd.**  
*Patna, Bihar | Mar 2018 – Aug 2022*
* **Mass OS Migration:** Spearheaded the corporate Windows 7 to Windows 10 enterprise migration for **180+ mission-critical endpoints** via SCCM PXE boot within an aggressive 6-week deadline.
* **Team Leadership & Mentorship:** Mentored 6 junior support engineers on ITIL incident handling and network troubleshooting, improving First Contact Resolution (FCR) by **22%**.
* **IT Asset Audits:** Maintained physical and network inventory records across 200+ systems with **96% audit accuracy**.
---
### **Technical Support Engineer**
**Client:** Rural Electrification Corporation (REC) — via Atlanta Systems  
*New Delhi | May 2015 – Mar 2018*
* **Multi-Branch Operations:** Provided tier 1/2 deskside and infrastructure support for 200+ corporate users across REC Headquarters and **15+ regional branch offices**.
* **Critical Incident Resolution:** Maintained high-availability network connectivity (VPN, LAN, DNS, Exchange Mailbox synchronization) with an average ticket turnaround under 4 hours in a highly regulated government sector client.
---
## 📜 Professional Certifications
* 🎓 **ITIL 4 Foundation in IT Service Management** — PeopleCert / Simplilearn
* 🎓 **macOS Support & Administration Essentials** — Apple / LinkedIn Learning
* 🎓 **Microsoft Copilot & AI Productivity Essentials** — Microsoft Press
* 🎓 **Python for IT Operations & Automation** — Google / Coursera
* 🎓 **Generative AI: Enterprise Prompt Engineering** — LinkedIn Learning
---
## 📬 Let's Connect & Collaborate
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/vikas-singh-816657ab)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-D14836?style=for-the-badge&logo=gmail)](mailto:vikaskumarsingh333@gmail.com)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=github)](https://vikas3333-singh.github.io/vikas-singh.github.io/)
*Available for Senior Workplace Services, Enterprise Deskside / VIP Support Lead, and Endpoint Operations roles.*
