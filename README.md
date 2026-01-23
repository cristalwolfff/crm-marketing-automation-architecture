# ☀️ Solar Eco Solutions: Enterprise CRM Architecture
*(Technical Case Study: Renewable Energy & Logistic Automation)*

![Salesforce Marketing Cloud](https://img.shields.io/badge/Stack-Salesforce_Marketing_Cloud-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![SQL](https://img.shields.io/badge/Data-SQL_Automation-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Industry](https://img.shields.io/badge/Industry-Solar_Energy_&_Utilities-F2C94C?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-LTV_&_Logistics_Automation-4B275F?style=for-the-badge)

> **Strategic CRM Architecture for Customer Lifecycle Management.**
> *Focus: Post-Purchase Psychology, App Adoption, and Logistics Orchestration.*

---

## 🎯 The Challenge
Design a robust CRM architecture for **Solar Eco Solutions** capable of mitigating "Buyer's Remorse" (High-Ticket Item), ensuring technical installation success, and driving the adoption of the Energy Monitoring App.

### 🚫 The Constraints (Engineering Challenge):
To demonstrate mastery of **fundamental logic**, this solution was architected with intentional limitations:
1.  **Single Channel:** Communication restricted to **Email Only**, demanding extreme relevance to maintain Open Rates.
2.  **Deterministic Logic (No-AI):** Solution designed without reliance on *Einstein* or "Black Box" predictive algorithms. It relies entirely on **hard-coded business logic** and **Structured Data Modeling**.

---

## 🏗️ Solution Architecture

### 1. Welcome Journey (Onboarding & Education)
The goal is not just a "Hello," but to validate a complex purchase and initiate behavioral change.
* **Neural Strategy:** Leveraging *Confirmation Bias* to reinforce the "smart financial decision" of going solar.
* **App Adoption:** Strategic nudges to drive App downloads, turning "Energy Monitoring" into a daily habit (The "Hook").
- [📄 View Visual Workflows](./journey.pdf)

---

### 2. Logistics Pipeline (Tracking & Installation)
A **decoupled** workflow focused exclusively on operations to reduce "No-Shows" and Customer Support (CS) ticket volume.
* **Trigger Logic:** Automated T-3 and T-1 reminders based on dynamic installation dates.
* **Crisis Management:** Fallback automation workflows for rescheduling in case of failed visits.
- [📄 View Visual Workflows](./logistica.pdf)

---

## 📊 Data Structure & KPIs
The intelligence of this project lies in the **Relational Data Modeling** (Data Extensions) that enables advanced personalization without AI.

| Strategic KPI | Business Goal | Technical Metric |
| :--- | :--- | :--- |
| **OPEX Reduction** | Decrease "When is my installation?" support tickets | Email Confirmation Rate / Ticket Volume |
| **App Stickiness** | Create a habit of checking daily energy savings | CTR on "View My Savings Graph" link |
| **NPS & Loyalty** | Convert financial savings into social proof | % of Promoters (9-10) converted to Reviews |

### 🛠️ Technical Implementation
* **SQL Automation:** Written complex queries in Automation Studio to sanitize raw data and calculate dynamic dates (T-3 logic).
* **Advanced AMPscript:** Implemented conditional logic within emails to render content based on real-time installation status.
* **CloudPages:** Developed custom landing pages for NPS capture and appointment confirmation.

---

## 📂 Full Documentation (Download)
Access the original files detailing the technical schema and visual journeys:

- 📕 **[Read Full Technical Documentation (PDF)](case_solar.pdf)**
- 🗺️ **[View Onboarding Diagram (PDF)](journey.pdf)**
- 🚛 **[View Logistics Diagram (PDF)](logistica.pdf)**

---
*Developed by [Cristalwolf](https://github.com/cristalwolfff) // AI Engineer & MarTech Specialist*
