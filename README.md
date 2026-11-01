#  Uncovering the Hidden Drivers of Employee Turnover | HR Analytics in Power BI

An end-to-end People Analytics dashboard built using **Power BI**, analyzing 1,470 employee records to help management shift from reactive hiring to proactive retention strategies.

---

##  Project Overview
Employee attrition isn’t just an HR metric—it’s a direct operational cost and a key indicator of organizational health. This project transforms raw workforce data into actionable intelligence, identifying the root causes of employee turnover.

---

##  Key Analytical Takeaways

- **The Overtime Burnout Multiplier:** Staff working overtime face a **30.5% attrition rate** versus just **10.4%** for non-overtime peers (a nearly 3x increase).
- **Frontline Vulnerability:** **Sales Representatives** experienced the steepest turnover at **39.8%**, followed by **Laboratory Technicians** at **23.9%**.
- **The Early-Tenure Pay Squeeze:** The lowest compensation tier (< $3.5k/month) experienced **27.1% turnover**, compared to ~10.5% in upper tiers. Flight risk peaks heavily within the first 0–10 years of service.
- **Compounded Dissatisfaction:** When poor work-life balance collided with low job satisfaction, turnover spiked dramatically to **47.1%**.

---

##  Technical Architecture & Implementation

### 1. Data Transformation & Modeling
- Conducted thorough data audits, verified integrity, and removed zero-variance columns.
- Implemented data-driven feature binning (Salary Tiers, Experience Bands, Age Groups).
- Designed a robust relational data model optimized for performance.

### 2. Custom DAX Measures
- Developed advanced DAX formulas for dynamic attrition rates, risk segment tracking, and filtered KPI monitoring.

### 3. Power BI Dashboard Layout
- **2-Page Executive Layout:** Featuring an *Executive Overview* for high-level stakeholders and an *Attrition Deep-Dive* for granular HR exploration.
- Designed with professional UI/UX standards to translate numbers into strategic workforce planning.

---

## 📁 Repository Structure
```text
├── assets/                  # Dashboard screenshots and preview images
├── data/                    # Cleaned dataset used for the visualization
├── PowerBI_Report/          # Power BI report file (.pbix)
└── README.md                # Project documentation
