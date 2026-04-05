# Applicant Outreach & Admissions Insights Dashboard

## Project Overview
This project analyzes applicant outreach activities, engagement patterns, geographic distribution, case progress, and admissions-related operational trends using Power BI.

The goal of the analysis was to transform raw outreach and applicant interaction data into actionable insights that can support recruitment strategy, outreach optimization, and case tracking improvements.

The final output includes an interactive Power BI dashboard, an insight report, and a stakeholder presentation.

---

## 📊 Tool Used
- Power BI
- Excel / CSV
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)

---

## 📁 Dataset
The dataset contains applicant outreach and admissions-related interaction records, with a focus on international graduate recruitment.

### Key fields used include:
- Reference_ID
- Country
- Degree_Type
- Intake
- College
- Caller_Name
- Outcome_1
- Admit_Date

### Dataset Summary:
- 7,543 records
- 5,000 unique students
- Originally 80 variables
- Reduced to 32 usable fields after cleaning

**Note:** The dataset included repeated interaction records, high sparsity, and multiple empty or inconsistent fields, which were cleaned and standardized before analysis.

---

## Problem Statement
Admissions and outreach teams often struggle to clearly understand:

- which countries and colleges contribute the most applicants,
- how outreach engagement is distributed,
- which case outcomes dominate the applicant journey,
- and where process inefficiencies may exist.

This project was designed to answer these questions by building a dashboard that supports better visibility into outreach performance and applicant case progress.

---

## Project Objectives
The main objectives of this analysis were to:

- Analyze applicant distribution across countries and colleges
- Understand degree type and intake patterns
- Examine outreach outcomes and case progress statuses
- Evaluate counselor activity and workload distribution
- Build an interactive dashboard for operational and strategic decision-making

---

## Process

### 1. Data Cleaning
- Dropped 38 empty columns
- Removed 146 duplicate records
- Standardized country and degree labels
- Fixed inconsistent date formats
- Selected a single clean date field for time-based analysis

### 2. Data Preparation
- Preserved repeated `Reference_ID` values where needed for interaction analysis
- Reduced the dataset to 32 usable analytical fields
- Excluded unreliable timestamp fields with low analytical value

### 3. Dashboard Development
Built an interactive Power BI dashboard covering:

- Country-level applicant trends
- College distribution
- Degree type analysis
- Outreach outcomes and case progress
- Counselor activity overview
- Intake-based patterns

---

## Key Insights

- Applicant records are highly concentrated in a few countries, with one country contributing the majority of records
- A limited number of colleges account for most applicant activity
- Graduate applicants dominate the dataset
- Follow-up and transcript-related statuses are the most frequent outcomes
- High volumes of repeated follow-ups suggest strong engagement but slow case resolution
- Counselor activity varies significantly across staff members

---

## Recommendations

- Improve completeness of degree type, country, and outcome fields
- Expand outreach into underrepresented countries
- Diversify partnerships beyond the top contributing colleges
- Refine case status tracking for better visibility into active vs resolved cases
- Introduce standardized counselor performance and workload metrics

---

## 📊 Dashboard Pages / Focus Areas

### 1. Geographic Distribution
Analyzes applicant volume by country and highlights regional concentration.

### 2. College & Degree Insights
Shows the most represented colleges and degree categories.

### 3. Outreach Outcomes & Case Progress
Examines the most common case statuses and engagement patterns.

### 4. Counselor Activity & Intake Trends
Tracks outreach activity by staff and identifies seasonal or intake-based patterns.

---

## 📸 Dashboard Preview

### Main Dashboard
![Main Dashboard](screenshots/main-dashboard.png)

### Country & Outreach Insights
![Country Insights](screenshots/country-insights.png)

### Case Progress & Counselor Activity
![Case Progress](screenshots/case-progress.png)

---

## 📂 Files Included

- `Excelerate Week3.pbix` – Power BI dashboard file
- `Insight Report.pdf` – Final written insight report
- `Team 11 Final Presentation.pptx` – Final stakeholder presentation
- `screenshots/` – Dashboard preview images
- `README.md` – Project documentation

---

## 🚀 Outcome
This project demonstrates my ability to:

- clean and structure operational datasets,
- build interactive dashboards in Power BI,
- identify strategic patterns in outreach and admissions data,
- and communicate insights clearly to stakeholders.

---

## 👩🏽‍💻 Author
**Abigail Alabi**  
Aspiring Data Analyst | Power BI | Excel | Data Storytelling
