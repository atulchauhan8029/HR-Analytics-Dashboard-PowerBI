# 👥 HR Analytics Dashboard | Employee Attrition (Power BI)

An interactive Power BI dashboard that analyses **employee attrition** across 1,470 employees to find *who leaves, when they leave and why*, so HR can make better retention and hiring decisions.

![Dashboard Preview](images/dashboard.png)

---

## 📌 Problem Statement
The company is losing employees and wants to understand the pattern behind it. This project answers:

1. How many employees left, and what is the attrition rate?
2. Which age groups, salary bands and job roles have the highest attrition?
3. Does attrition depend on education, years at the company or job satisfaction?
4. What can HR do to reduce attrition?

---

## 🛠️ Tools & Skills Used
- **Power BI Desktop**: dashboard design, interactive visuals
- **DAX**: measures such as Attrition Count and Attrition Rate
- **Data modelling & preparation**: custom columns such as *Age Group* and *Salary Slab*
- **Data visualisation & storytelling**

---

## 📂 Project Structure
```
HR-Analytics-Dashboard-PowerBI/
├── README.md
├── dashboard/
│   └── HR_Analytics_Dashboard.pbix     ← open with Power BI Desktop (free)
├── data/
│   └── HR_Employee_Attrition.csv       ← dataset used
├── images/
│   ├── dashboard.png                   ← full dashboard
│   └── ...                             ← optional close-ups
└── docs/                               ← optional PDF export
```

> 💡 To explore the dashboard, download `HR_Analytics_Dashboard.pbix` and open it in the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

---

## 📊 Dashboard Contents

**KPI cards:** Total Employees · Attrition · Attrition Rate · Average Age · Average Years at Company · Average Monthly Income

**Visuals:**
| Visual | Question it answers |
|---|---|
| Attrition by Education Field (donut) | Which education backgrounds leave most? |
| Attrition by Age Group (column) | Which age group leaves most? |
| Attrition by Years at Company (area) | When in their career do people leave? |
| Attrition by Salary Slab (bar) | Does low pay drive attrition? |
| Attrition by Job Role (bar) | Which roles are at risk? |
| Attrition by Gender (pie) | How does attrition split by gender? |
| Job Role × Job Satisfaction (matrix) | Where do satisfaction and role combine to cause exits? |

---

## 🔑 Key Numbers
| Metric | Value |
|---|---|
| Total employees | **1,470** |
| Employees who left | **237** |
| Attrition rate | **16.1%** |
| Average age | **37** |
| Average years at company | **7.01** |

---

## 🔍 Key Insights
- **Age 26–35** has the highest attrition (116 of 237 leavers, about **49%**).
- **Low income** is a major factor: employees earning **up to 5k** account for 163 leavers (about **69%**).
- **Laboratory Technician, Sales Executive and Research Scientist** together make up about **70%** of all leavers (166 of 237).
- Most employees who leave do so **early in their career at the company**, in the first 1–2 years.
- **Life Sciences and Medical** education backgrounds account for about 65% of leavers.

---

## ✅ Recommendations
1. **Review pay** for the lowest salary band, where attrition is highest.
2. **Strengthen onboarding and early-career support** in the first two years.
3. **Run retention programmes** for the three highest-risk roles.
4. **Focus engagement efforts on employees aged 26–35.**
5. **Track job satisfaction** regularly and act on low scores.

---

## 🧠 Project Learnings
- Identified the key factors that drive attrition
- Insights to improve the hiring process
- Insights to improve employee experience
- Ways to make the workforce more productive
- Ways to build employee trust through data-driven decisions

---

## 📐 Key DAX Measures
```DAX
-- Paste your own measures here, for example:
Attrition Rate = DIVIDE ( [AttritionCount], [Employee Count] )
```

---

## 📎 Dataset
- File: `data/HR_Employee_Attrition.csv` (1,470 employee records)
- Source: [add the source / link of your dataset here]
- This is a **practice dataset** used for learning. It contains no real personal data.

---

## 👤 Author
**Atul Chauhan**
