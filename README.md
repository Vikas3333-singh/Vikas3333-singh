# Hi, I'm Vikas Singh 👋
### Senior End User Support & Workplace Technology Specialist | 11+ Years Experience
**L1/L2 Deskside & VIP Support • Windows & macOS • Microsoft 365 • Entra ID • Intune & Autopilot • ServiceNow (ITIL 4) • 95%+ SLA**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-singh-816657ab)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vikaskumarsingh333@gmail.com)
[![Portfolio](https://img.shields.io/badge/Executive_Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vikas3333-singh.github.io/vikas-singh.github.io/)
📍 **Gurugram, Haryana, India** | 🎯 **Focus:** Senior Workplace Services • VIP Deskside Operations • Enterprise Endpoint Automation
> *"Over 11+ years of hands-on expertise managing enterprise end-user computing (EUS), delivering white-glove VIP support for tier-1 management consulting environments (including Boston Consulting Group), and automating Lenovo/Apple fleet lifecycle management."*
---
## Executive Career Snapshot (Real Operational Impact)
| Metric | Baseline (Manual) | Optimized (Automated) | Strategic Business Impact |
| :--- | :--- | :--- | :--- |
| **Device Staging Touch-Time** | ~150 mins per laptop | **<20 mins hands-on time** | 85% engineer time saved via Lenovo Driver Packs & Autopilot |
| **Endpoint Diagnostic MTTR** | 35–45 mins per ticket | **4.5 mins automated run** | 88.7% MTTR reduction via dual-OS maintenance utility |
| **Fleet Patch Compliance** | 82%–88% (fluctuating) | **97%+ consistent** | Zero critical CVE vulnerabilities across 500+ endpoints |
| **SLA Adherence (P1–P5)** | ~89% baseline | **95.4% SLA adherence** | Adherence maintained consistently in ServiceNow (ITIL 4) |
| **Docking / Peripheral Tickets** | High post-deployment issues | **60% reduction** | Automated Lenovo Thunderbolt/USB-C dock firmware pre-checks |
| **Executive / VIP Meetings** | Occasional AV/laptop glitches | **100% Zero-Downtime** | White-glove IT support for 30+ Partner/Director townhall sessions |
---
## Core Technical Competencies 

┌─────────────────────────────────┬─────────────────────────────────────────────────────────┐
│ Domain                          │ Enterprise Technology Stack                             │
├─────────────────────────────────┼─────────────────────────────────────────────────────────┤
│ Endpoint Management (MDM/MAM)   │ Microsoft Intune, MECM / SCCM, Jamf Pro, Autopilot      │
│ OEM & Fleet Engineering         │ Lenovo ThinkPad (T/X1 Series), Lenovo Commercial Vantage│
│                                 │ Lenovo Thin Installer, System Update, Thunderbolt Docks │
│ Identity & Access (IAM)         │ Microsoft Entra ID (Azure AD), M365 Admin, SSO, MFA, RBAC│
│ Operating Systems & Platforms   │ Windows 10/11 Enterprise, macOS (Ventura–Sequoia), iOS  │
│ ITSM & Frameworks               │ ServiceNow (Incident/Change/Problem/Asset), ITIL 4      │
│ Automation & Scripting          │ PowerShell, Bash (POSIX), Batch, WMI/CIM Queries        │
│ Executive / Deskside Support    │ VIP White-Glove Support, Townhall AV, Teams Rooms / Zoom │
│ Infrastructure & Networking     │ TCP/IP, DNS, DHCP, GlobalProtect / Cisco AnyConnect VPN  │
└─────────────────────────────────┴─────────────────────────────────────────────────────────┘

---
## 🏆 Featured Engineering Case Studies
### 1. Lenovo ThinkPad Fleet Staging & Docking Firmware Standardization
*Automating OEM Drivers, BIOS Baselines, and Peripheral Reliability for Enterprise Laptops*
* **The Problem (Kya problem thi):** Fresh deployment of enterprise Lenovo laptops (ThinkPad T14, X1 Carbon, L-series) required technicians to spend ~2.5 hours per machine manually installing drivers, configuring BIOS/TPM, and resolving frequent post-delivery display flickering and disconnects on Lenovo Thunderbolt/USB-C docks.
* **The Action (Maine kya kiya):**
  * Integrated **Lenovo Thin Installer & Driver Integration Packs** into the deployment pipeline to automate driver injection silently.
  * Engineered a PowerShell post-staging script querying Lenovo WMI classes (`root\wmi:Lenovo_BiosSetting`) to standardize BIOS settings (Secure Boot, TPM 2.0, Wake-on-LAN, Password policy) without entering BIOS manually.
  * Established a mandatory automated dock firmware update workflow prior to user delivery.
* **The Output (Kya result aaya):**
  * Technician hands-on time dropped from **150 minutes to under 20 minutes per device** (remaining steps unattended).
  * First-week dock disconnection and external display tickets dropped by **over 60%**.
* **The Business Benefit (Output se kya fayda mila):**
  * Guaranteed hardware stability on Day 1 for traveling consultants and executives.
  * Eliminated manual technician errors and accelerated bulk hardware refresh cycles during office laptop renewal programs.
---
### 2. [Advanced IT Troubleshooting Utility (AITU)](https://github.com/Vikas3333-singh)
*Cross-Platform Automated Diagnostic & Maintenance Engine for Windows & macOS*
* **The Problem (Kya problem thi):** Support engineers spent 35–45 minutes manually cleaning caches, running SFC/DISM repairs, and checking hardware on degraded endpoints. No silent MDM push was possible, creating ticket backlogs.
* **The Action (Maine kya kiya):** Engineered a native dual-OS automation suite (`maintenance.sh` & `windows_maintenance_final.bat`) featuring 15 silent CLI switches for Intune/SCCM, atomic PID locking, non-destructive `--dry-run` modes, and a conversational issue-routing triage engine.
* **The Output (Kya result aaya):** Maintenance time dropped from **40 minutes to under 4.5 minutes** with automated 90-day JSON health telemetry.
* **The Business Benefit (Output se kya fayda mila):** **88.7% MTTR reduction**, 74% reduction in L2 escalations, and zero-touch background execution without disturbing business meetings.
---
### 3. Modern Workplace Zero-Touch Provisioning (Autopilot & Intune)
*Self-Service Cloud Deployment Pipeline for Remote & Hybrid Staff*
* **The Problem (Kya problem thi):** Imaging remote and hybrid employees' laptops required physical staging at the Gurugram office, shipping back and forth, and lengthy phone onboarding with support staff.
* **The Action (Maine kya kiya):** Configured **Windows Autopilot (User-Driven Entra ID Join)** integrated with Microsoft Intune, pre-assigning configuration profiles, BitLocker encryption policies, and required M365 application bundles based on dynamic Entra ID user groups.
* **The Output (Kya result aaya):** Allowed devices to be drop-shipped directly from the vendor to end users; user logs in with corporate M365 credentials, and the laptop automatically provisions in ~45 minutes unattended over Wi-Fi.
* **The Business Benefit (Output se kya fayda mila):** Eliminated IT shipping and double-handling costs, delivered true out-of-the-box Day-1 readiness, and saved 30+ technician hours during high-volume hiring months.
---
### 4. [IT Asset Tracker & Hardware Lifecycle Dashboard](https://github.com/Vikas3333-singh/it-asset-tracker)
*Real-Time Enterprise Asset Governance & Compliance Platform*
* **The Problem (Kya problem thi):** Reconciling physical laptop inventory across remote and on-premise staff required 4 hours every week of manual Excel cross-matching, causing inventory leakage and untracked depreciation.
* **The Action (Maine kya kiya):** Built a web-based ITAM dashboard utilizing JavaScript, Chart.js, and automated log parsers to track lifecycle status, assigned consultants, warranty expiry, and device health.
* **The Output (Kya result aaya):** Weekly audit time decreased from **4 hours/week down to under 20 minutes** with live visualization.
* **The Business Benefit (Output se kya fayda mila):** Eliminated ghost assets, achieved **99%+ audit compliance**, and prevented costly software license overages.
---
## 💼 Professional Experience (11+ Years)
### **System Analyst (End User & Workplace Services)**
**Client:** Boston Consulting Group (BCG) — via Konverge Technologies  
*Gurugram, Haryana | Aug 2022 – Present*
* **Enterprise Fleet Governance:** Administer 500+ heterogeneous endpoints (Lenovo ThinkPad, macOS, Mobile) across BCG offices ensuring **97%+ patch compliance** against zero-day CVE vulnerabilities.
* **VIP White-Glove Support:** Dedicated deskside support lead for Partners, Managing Directors, and Practice Area Leaders; provided zero-downtime support for 30+ critical tier-1 meetings and executive townhalls.
* **OEM Hardware Lifecycle:** Managed procurement, warranty ticketing, dock firmware updates, and repair dispatch with Lenovo Enterprise Support and Apple Premier Support.
* **Modern IAM Operations:** Manage Entra ID (Azure AD) lifecycle, Conditional Access policies, automated group memberships, and MFA enforcement adhering strictly to global zero-trust principles.
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
