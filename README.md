# SYNTECXHUB-PROJECT-3
# HR Analytics Dashboard — Employee Attrition Analysis

An interactive Power BI dashboard analyzing employee attrition across departments, job roles, demographics, and compensation — built as Project 3 of my Data Analytics Internship at **Syntecxhub**.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

---

## 📥 How to View This Dashboard

This is a Power BI file (`.pbix`), so it can't be previewed directly in the browser — GitHub only lets you download it.

1. Click on the `.pbix` file in the repo's file list
2. Click **Download raw file** (or **"View raw"**) to save it to your computer
3. Open it using **[Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)** (free to download from Microsoft)

Don't have Power BI Desktop or just want a quick look? Screenshots are included below.

---

## 📊 Project Overview

This dashboard investigates why employees leave the organization and identifies which groups are most at risk of attrition. It combines headline KPIs, demographic breakdowns, tenure trends, and role/department-level detail to help HR teams prioritize retention efforts.

**Key metrics tracked:** Headcount, Attrition Count, Attrition Rate, Average Salary, Average Age, Average Tenure

---

## 🔑 Key Findings

- **Overall attrition rate: 16.08%** across 1.47K employees (238 total attritions)
- **Attrition skews male:** 63.45% of attritions are male employees vs. 36.55% female
- **Frequent business travelers attrite most:** 157 attritions among employees who travel frequently, vs. only 12 among non-travelers
- **Research & Development is hit hardest:** 65.34% of all attritions come from this department
- **Younger employees are highest risk:** the 26–35 age group has the highest attrition rate at 35.77%, followed by 18–25 at 18.99%
- **Early tenure is the danger zone:** attrition spikes heavily within the first 1–3 years at the company, then drops off sharply after year 5
- **Compensation matters:** 163 of the lowest-paid employees (up to 5K salary slab) accounted for the largest share of attrition — far more than any higher salary band
- **Job satisfaction correlates with departure:** the JobRole × Satisfaction matrix shows Sales Executives and Laboratory Technicians with the highest attrition concentrated at satisfaction level 1 (lowest)

---

## 🗂️ Dashboard Sections

| Visual | What it shows |
|---|---|
| KPI Cards | Headcount, Attrition Count, Attrition Rate, Avg Salary, Avg Age, Avg Tenure at a glance |
| Attrition Count by Gender | Male vs. female attrition split |
| Attrition Count by BusinessTravel | Attrition by travel frequency |
| Attrition by Department | Department-level attrition share (donut) |
| Attrition by YearsAtCompany | Attrition trend across tenure length |
| AttritionCount and Attrition Rate by AgeGroup | Combo chart comparing volume vs. rate across age brackets |
| Years At Company and Attrition by EducationField | Tenure and attrition broken down by education background |
| Attrition Count by SalarySlab | Attrition concentration across salary bands |
| JobRole × Satisfaction Matrix | Cross-tab of job role against satisfaction score (1–5), with attrition totals |
| Slicers | Filter by AgeGroup, Department, and EducationField |

---

## 🎨 Design

- Dark forest-green theme for a professional, focused analytics feel
- Consistent card-based layout with rounded containers for each visual
- Combo charts (bar + line) used to show volume and rate together without cluttering the page
- Interactive slicers for on-the-fly filtering by AgeGroup, Department, and EducationField

---

## 🛠️ Tools & Skills Used

- Power BI Desktop (data modeling, DAX, visuals)
- DAX measures for attrition rate, averages, and cross-tabulated counts
- Matrix visual with conditional formatting for role/satisfaction analysis
- Combo charts (clustered column + line) for dual-metric comparisons
- Data storytelling for HR/stakeholder-facing insights

---

## 📌 About This Project

This is Project 3 of my Data Analytics Internship at Syntecxhub, focused on HR analytics and attrition modeling. It builds on data modeling and DAX skills developed in earlier projects (Superstore Sales Dashboard and RFM Customer Segmentation) by applying them to a workforce analytics use case.

**Author:** Mercy ([@Mercy727](https://github.com/Mercy727))

