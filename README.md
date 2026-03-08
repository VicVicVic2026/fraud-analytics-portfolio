# Fraud Analytics Portfolio
### Victor Viquez | Fraud Operations Specialist | CFE Candidate 2026
**Skills demonstrated:** SQL · Power BI · BSA/AML · Fraud Typology Analysis

---

## About This Portfolio
This portfolio contains fraud detection case studies built using 
fictional data to demonstrate analytical thinking, BSA/AML 
compliance knowledge, and fraud investigation skills developed 
over 3+ years in fraud operations at a major U.S. bank.

---

## Project 1: BSA/AML Fraud Detection Analysis

### Business Problem
Financial institutions must identify and escalate high-risk 
customer activity that may indicate money laundering, fraud, 
or terrorist financing. This project simulates a real fraud 
alert management workflow used in bank fraud operations.

### Database Design (SQL Server)
Built a relational database with three tables:

**Customers table** — includes risk rating (LOW/MEDIUM/HIGH), 
country of origin, account type, and PEP (Politically Exposed 
Person) flag for AML screening

**Fraud Alerts table** — tracks alert type, status 
(SAR_FILED / ESCALATED), assigned analyst, and case notes

**Transactions table** — links to customer and alert records 
for transaction-level analysis

### Fraud Typologies Analyzed
- Account Takeover — Unauthorized Access
- Card Testing — Rapid Low Value Transactions
- Structuring — Multiple Sub-$10K Cash Deposits
- PEP — Large Incoming Wire Rapid Outbound
- Dormant Account Reactivation — Unusual Cash
- Zelle Romance Scam — Escalating Transfers

### Key Findings
- 66.67% of flagged alerts resulted in SAR filings
- 33.33% were escalated for further investigation
- HIGH risk customers accounted for the majority of 
  SAR-filed cases
- PEP-flagged accounts showed the largest average 
  transaction amounts

### Tools Used
- Microsoft SQL Server (Azure Data Studio)
- Power BI Desktop
- Fictional dataset created for portfolio demonstration

---

## Certifications & Credentials
- Certified Fraud Examiner (CFE) — In Progress, 2026
- eCornell Cybersecurity Certificate — In Progress, 2026
- SQL for Data Analysis (Intermediate) — Completed Feb 2026
- Advanced KYC & AML Essentials — Certified

---

## Professional Background
3+ years at Regions Bank as Fraud Operations & Priority 
Banking Specialist — bilingual fraud triage (EN/ES), 
Zelle/ACH dispute intake, Reg E/Z compliance, KYC/CIP 
onboarding, BSA/AML red flag identification
