# HR Attrition & Turnover Analysis – Power BI Portfolio Project

![1](https://github.com/user-attachments/assets/4662b1db-2d31-4d2c-90f9-1028d991f723)

![2](https://github.com/user-attachments/assets/b4d9ebd5-eb4b-4f77-8b9d-aeca3a1bd3b9)

![1](https://github.com/user-attachments/assets/73bcb093-ac1e-4989-be57-bcab6a4ac1cd)

---

---

##  Project Overview

Analyzed employee attrition patterns across demographics, job roles, departments, compensation, and engagement factors using Power BI. The dashboards consolidate HRIS, survey, and payroll data to **uncover attrition drivers, quantify financial impact, and recommend data-backed interventions** — turning HR data into business performance intelligence.

---

##  Executive Summary

| Metric | Value |
|---|---|
| Overall Attrition Rate | 16% |
| Life Sciences Attrition | 39% (2.3× company average) |
| Annual Cost — Life Sciences | ₹2.8 Cr in replacement + lost productivity |
| Female R&D Representation | Only 6% (37 out of 587 roles) |
| Projected Annual Savings (if recommendations implemented) | ₹3.1 Cr |
| Highest Risk Age Group | 26–35 years (avg tenure 3.2 years) |
| Salary–Satisfaction Correlation | r = 0.57 |

---

##  Key Findings

### 1.  Attrition Hotspots

| Role / Department | Exits | Key Driver |
|---|---|---|
| Life Sciences | 39% attrition rate | Limited career growth paths |
| Laboratory Technicians | 62 exits | Low engagement, early-tenure churn |
| Sales Representatives | 53 exits | High travel pressure and performance stress |

### 2.  Gender Imbalance in Technical Roles
- R&D has only **6% female representation** (37 women out of 587 roles)
- Limits diversity of thought and reduces innovation capacity
- **Target:** Raise female R&D representation to **15% within 12 months**

### 3.  Tenure & Satisfaction Risk Zones

| Age Group | Avg Tenure | Satisfaction | Risk Level |
|---|---|---|---|
| 18–25 | 1.1 years | Low | Medium |
| 26–35 | 3.2 years | 3.7 / 5 | **High** |
| 36–55 | 6.4 years | High | Low |

### 4.  Compensation & Engagement Link
- Salary vs Satisfaction correlation: **r = 0.57**
- Bottom quartile (₹4.2L avg) → Satisfaction: **3.5 / 5**
- Top quartile (₹11.4L avg) → Satisfaction: **4.3 / 5**
- Clear evidence: **underpaying increases attrition risk**

### 5. ⏰ Performance & Overtime Impact
- Low performance employees: **15.6% of attrition cases** — often disengagement, not underperformance
- Overtime workers: **127 exits** vs non-overtime: **110 exits** — burnout is a measurable attrition driver

---

##  Business Recommendations & 12-Month OKRs

| Initiative | Owner | Metric | Target |
|---|---|---|---|
| Life Sciences Career Ladder | HRBP | Attrition % | 39% → 15% |
| Women-in-Tech Scholarship | Talent Dev | Female R&D % | 6% → 15% |
| Manager Upskilling Program | L&D | Manager eNPS | +12 → +35 |
| Exit Interview Dashboard | People Analytics | Insights Actioned | 80% |
| Salary Band Transparency | Comp & Ben | Bottom Quartile Satisfaction | 3.5 → 4.0 |

---

## 📈 Projected Business Impact

If the organization implements all recommendations:

| Action | Current | Target |
|---|---|---|
| Life Sciences Attrition | 39% | 15% |
| Female R&D Representation | 6% | 15% |
| Bottom Quartile Satisfaction | 3.5 / 5 | 4.0 / 5 |
| **Projected Annual Savings** | — | **₹3.1 Cr** |

Additional gains: Higher innovation capacity, improved employer brand, reduced recruitment costs.

---

##  Data Sources Used

| Source | Data Provided |
|---|---|
| HRIS | Employee demographics, job roles, tenure, department |
| Payroll | Monthly income, salary quartiles |
| Engagement Surveys | Job satisfaction scores, eNPS |
| Exit Interviews | Attrition reasons and patterns |
| ATS / Recruitment Data | Hiring pipeline and replacement costs |

---

##  Technical Approach

### Power BI
- **Star schema** data model connecting HR, payroll, and survey data
- **DAX measures** for attrition rate, cost of attrition, satisfaction scores, and gender ratios
- **Interactive filters** by department, role, gender, tenure, and salary quartile
- **Drill-through pages** for attrition by education, performance, and overtime
- **KPI cards** for attrition %, active employees, gender ratio, and cost of attrition
- **Correlation plots** for salary vs satisfaction analysis
- **Executive snapshot page** with quantified business impact

### Power Query
- ETL pipeline: data cleaning, transformation, and normalization
- Merging HRIS, payroll, and survey datasets into unified model

### SQL
- Data extraction using JOINs across HR tables
- Aggregations for department-wise and role-wise KPI calculation

### Excel
- PivotTable analysis for preliminary data exploration
- Advanced charting and VBA automation for data preparation

---

##  Repository Structure

```
 HR-Talent-Analytics
├── 📄 HR_Analysis.sql               — SQL data extraction scripts
├── 📊 HR_Attrition_Dashboard.pbix   — Interactive Power BI dashboard
├── 🖼️  HR Analytics Dashboard.jpg    — Dashboard preview
└── 📄 README.md                     — Project documentation
```

---

##  Dashboard Preview

![HR Attrition Dashboard](HR%20Analytics%20Dashboard.jpg)

---

##  About

**Khurram Naveed** — Data Analyst specializing in Power BI, SQL, and business intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/khurramnaveed3233)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/Khurramnaveed3233)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:khurramnaveed4545@gmail.com)

---

>  *This project demonstrates that HR data is business performance data. By combining Power BI visualization, DAX calculations, and business storytelling, we move from descriptive reporting to prescriptive action — turning people analytics into measurable ROI.*
