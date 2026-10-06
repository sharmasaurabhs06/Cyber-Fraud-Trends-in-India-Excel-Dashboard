# 🛡️ Cyber Fraud India Analysis Dashboard

An interactive **Cyber Fraud Analysis Dashboard** built to analyze cyber fraud incidents across India using **Excel, Pivot Tables, Data Analysis, and Data Visualization**.

This project focuses on identifying fraud patterns, financial losses, affected demographics, geographical trends, reporting channels, and actions taken against cyber fraud incidents.

---

## 📊 Project Overview

Cyber fraud is becoming a major concern with the increasing use of digital payments, online banking, social media, and e-commerce.

This project analyzes **20,000 cyber fraud incidents** recorded across India from **2021 to 2026** to understand:

- Which fraud types are most common
- Which fraud types cause the highest financial losses
- Which states experience the highest losses
- Which age groups are most affected
- Gender-wise distribution of victims
- How incidents are reported
- What actions are taken after reporting
- How cyber fraud incidents and losses change over time

The final output is an **Excel-based interactive dashboard** designed to make the analysis easy to understand and useful for decision-making.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze cyber fraud incidents across different years.
- Identify the most common types of cyber fraud.
- Analyze total financial losses caused by cyber fraud.
- Identify states with higher financial losses.
- Understand victim demographics.
- Analyze fraud reporting channels.
- Analyze actions taken after fraud reporting.
- Categorize fraud losses into Low, Medium, and High.
- Create meaningful KPIs and visualizations for better decision-making.

---

## 📁 Dataset

The dataset contains **20,000 cyber fraud records** with **13 columns**.

### Dataset Columns

| Column | Description |
|---|---|
| `Incident_ID` | Unique ID assigned to each fraud incident |
| `Date` | Date when the incident occurred/reported |
| `Year` | Year of the incident |
| `Month` | Month of the incident |
| `State` | Indian state where the incident occurred |
| `District` | District associated with the incident |
| `Fraud_Type` | Type of cyber fraud |
| `Victim_Age_Group` | Age group of the victim |
| `Victim_Gender` | Gender of the victim |
| `Amount_Lost_INR` | Financial loss caused by the incident |
| `Action_Taken` | Action taken after reporting |
| `Reported_By` | Channel through which the incident was reported |
| `Loss_Category` | Low, Medium, or High loss category |

---

## 📌 Dataset Statistics

- **Total Incidents:** 20,000
- **Time Period:** 2021 – 2026
- **States Covered:** 20
- **Districts Covered:** 30
- **Fraud Types:** 14
- **Total Financial Loss:** ₹5.00 Billion approximately
- **Average Loss per Incident:** ₹250K approximately

---

## 🔎 Fraud Types Analyzed

The project analyzes 14 different types of cyber fraud:

- UPI Fraud
- Phishing
- Ransomware
- OTP Fraud
- Online Shopping Scam
- Debit Card Fraud
- Lottery Scam
- Social Media Hacking
- SIM Swap
- Credit Card Fraud
- Investment Scam
- Data Breach
- Identity Theft
- Job Scam

---

## 📈 Key Performance Indicators (KPIs)

The dashboard focuses on important KPIs such as:

### 💰 Total Financial Loss
**₹5.00 Billion+**

Represents the total amount lost across all recorded cyber fraud incidents.

### 🚨 Total Fraud Incidents
**20,000**

Total number of cyber fraud cases analyzed.

### 📊 Average Loss per Incident
Approximately **₹250K**

Shows the average financial impact of each incident.

### 🗺️ States Covered
**20 States**

Provides geographical analysis of cyber fraud across India.

### 🔐 Fraud Categories
**14 Fraud Types**

Allows comparison between different cyber fraud methods.

---

## 📊 Dashboard Analysis

The dashboard provides analysis across multiple dimensions.

### 1. 📅 Year-wise Analysis

The project analyzes cyber fraud incidents and financial losses over time.

The highest number of incidents in the dataset is observed around **2025**, with more than **4,000 incidents**.

The yearly analysis helps identify changes in:

- Number of incidents
- Total financial loss
- Average loss per incident

---

### 2. 💳 Fraud Type Analysis

Different fraud types were compared based on incident volume and financial loss.

The highest total financial losses were observed in:

1. **UPI Fraud**
2. **Phishing**
3. **Ransomware**
4. **OTP Fraud**
5. **Online Shopping Scam**

This analysis helps identify the fraud methods that have the largest financial impact.

---

### 3. 🗺️ State-wise Analysis

The dashboard compares cyber fraud losses across Indian states.

Some of the states with the highest total financial losses include:

| Rank | State |
|---|---|
| 1 | Maharashtra |
| 2 | Tamil Nadu |
| 3 | Himachal Pradesh |
| 4 | Punjab |
| 5 | Uttarakhand |
| 6 | Karnataka |
| 7 | Jharkhand |
| 8 | Chhattisgarh |
| 9 | Kerala |
| 10 | Bihar |

This analysis helps identify geographical areas where cyber fraud has a higher financial impact.

---

### 4. 👥 Victim Demographic Analysis

The dashboard analyzes victims based on:

- Age group
- Gender

### Age Groups

- Under 18
- 18–25
- 26–35
- 36–45
- 46–60
- 60+

### Gender

- Male
- Female
- Other

This helps understand which demographic groups are affected by cyber fraud.

---

### 5. 📢 Reporting Channel Analysis

The dataset contains multiple reporting channels:

- Bank
- Self Report
- Cyber Cell
- Helpline
- Local Police

**Bank** is the most frequently represented reporting channel in the dataset.

This analysis helps understand where victims primarily report cyber fraud incidents.

---

### 6. 👮 Action Taken Analysis

The dashboard analyzes the action taken after an incident was reported.

The available actions are:

- Under Investigation
- Complaint Filed
- Resolved
- No Action
- FIR Registered

This provides an overview of how reported cyber fraud cases are handled.

---

### 7. 💸 Loss Category Analysis

Fraud losses are categorized into:

- 🟢 Low
- 🟡 Medium
- 🔴 High

The dataset contains:

- **High Loss:** 12,049 incidents
- **Medium Loss:** 6,008 incidents
- **Low Loss:** 1,943 incidents

This shows that a significant portion of the recorded incidents falls under the **High Loss** category.

---

## 💡 Key Insights

Some important insights obtained from the analysis are:

### 🔹 1. UPI Fraud has the highest financial impact

Among the analyzed fraud categories, **UPI Fraud** recorded the highest total financial loss.

### 🔹 2. 2025 shows a high number of incidents

The year 2025 recorded more than **4,000 incidents**, making it one of the most significant years in the dataset.

### 🔹 3. Maharashtra has the highest total loss

Maharashtra recorded the highest total financial loss among the states included in the dataset.

### 🔹 4. High-loss incidents dominate

The majority of incidents are classified under the **High Loss** category.

### 🔹 5. Banks are a major reporting channel

Bank-related reporting represents the largest reporting category in the dataset.

### 🔹 6. Cyber fraud affects multiple age groups

The data shows that cyber fraud is not restricted to a particular age group and affects victims across all analyzed age categories.

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Preparation
     ↓
Exploratory Data Analysis
     ↓
Pivot Tables
     ↓
KPI Calculation
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

## 📂 Project Structure

```text
Cyber-Fraud-Trends-in-India-Excel-Dashboard/
│
├── 📁 Dashboard/
│   └── 🖼️ Cyber_Fraud_Dashboard.png
|
├── 📁 Data/
│   └── 📄 data_project_cyber_fruad_sample.xlsx
│
├── 📁 Excel/
│   └── 📊 Cyber Fraud India Dashboard.xlsx
│
└── 📄 README.md
```

> Replace the file names above with your actual GitHub file names if they are different.

---

## 📊 Dashboard Features

The dashboard provides:

- 📌 KPI Cards
- 📈 Year-wise Trend Analysis
- 💳 Fraud Type Analysis
- 🗺️ State-wise Analysis
- 👥 Age-wise Analysis
- ⚧️ Gender-wise Analysis
- 📢 Reporting Channel Analysis
- 👮 Action Taken Analysis
- 💰 Loss Category Analysis
- 🔎 Interactive Filters
- 📊 Comparative Charts

---

## 💼 Business Questions Answered

This dashboard helps answer questions such as:

1. How many cyber fraud incidents occurred?
2. What is the total financial loss?
3. Which fraud type causes the highest financial loss?
4. Which states have the highest fraud losses?
5. Which age groups are most affected?
6. How are victims reporting fraud?
7. What actions are being taken after reporting?
8. What percentage of incidents fall into high-loss categories?
9. How are fraud incidents changing over time?
10. Which areas require greater attention for fraud prevention?

---

## 🚀 Future Improvements

The project can be further enhanced by:

- Adding **SQL** for data extraction and analysis.
- Using **Python Pandas** for automated data cleaning.
- Using **Matplotlib & Seaborn** for advanced visualization.
- Rebuilding the dashboard in **Power BI**.
- Adding interactive geographical maps.
- Creating automated monthly reports.
- Adding predictive analysis to identify future fraud trends.
- Building a fraud-risk prediction model using Machine Learning.

---

## 📌 Project Outcome

This project demonstrates how raw cyber fraud data can be transformed into meaningful business insights through:

**Data Cleaning → Analysis → Visualization → Dashboard → Insights**

The dashboard makes it easier to identify fraud patterns, understand financial impact, compare geographical regions, and analyze victim demographics.
---

### 📌 Tags

`#DataAnalytics` `#DataAnalyst` `#ExcelDashboard` `#CyberFraud` `#DataVisualization` `#Excel` `#Dashboard` `#EDA` `#BusinessIntelligence` `#DataScience`
