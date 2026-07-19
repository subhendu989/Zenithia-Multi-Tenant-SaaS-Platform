# Zenithia Multi-Tenant SaaS Coaching & Education Platform - QA Automation & Manual Testing Log

This repository contains the comprehensive Software Quality Assurance (SQA) artifacts, manual test case execution logs, and defect tracking reports for the **Zenithia Multi-Tenant SaaS Coaching & Education Platform**. 

The main objective of this project was to validate core business workflows, multi-role access controls, billing modules, and configuration setups to ensure production-grade system stability.

---

## 📋 Project Overview
* **Application Type:** Multi-Tenant SaaS (Software-as-a-Service)
* **Target Domains:** Student Fees Billing, Exam Management, Admin Settings, Theme Customization, and Certificate Generation.
* **Testing Types:** Functional Testing, Access Control Auditing, Validation Testing, and Cross-Browser Matrix Execution.
* **Environment Configuration:**
  * **Browser:** Chrome v150 (Build: 150.0.7871.47)
  * **OS:** Windows 11 (64-bit)

---

## 🔍 Key Accomplishments & Bugs Analyzed
During the test cycles, **18 verified functional defects** were uncovered, documented, and cataloged. Key focus areas included:
1. **Critical Functional Blockers:** Diagnosed major UI form freezes on core modules (Create Exam, Theme Editor, and Certificate Generation) where forms failed valid data processing and lacked required field triggers.
2. **Access Control & Routing Flaws:** Discovered high-priority vulnerabilities including broken `404 Not Found` paths on staff onboarding flows and duplicate role invitations.
3. **Data Integrity & Validations:** Identified critical validation gaps such as missing duplicate email entry blocks and unforced required inputs for system roles.

---

## 📁 Repository Structure
```text
├── Zenithia_Platform_Standard_Tenant_Bug_Log_v2.xlsx   # Full Detailed Bug Log Sheet
├── README.md                                           # Project Documentation
└── screenshots/                                        # Evidence & Defect Screenshots (To be added)



```
🛠️ Tools & Technologies Used
Test Management / Tracking: Microsoft Excel / Google Sheets

Defect Profiling: Chrome DevTools

Automation Ready Frameworks: Playwright (configured for parallel test pipelines)
```
