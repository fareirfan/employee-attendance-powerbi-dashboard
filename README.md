# 👥 Employee Attendance Power BI Dashboard

> **Building the first-ever attendance visibility system for a department — from security swipe logs to actionable workforce insights.**

---

## 📌 Project Overview

One of the department had **no dedicated system** to monitor workforce attendance patterns. Shift adherence, overtime utilization, absence trends, and headcount visibility were either tracked informally or not tracked at all — leaving engineering managers without reliable data to support resource planning decisions.

This project filled that gap entirely. By transforming raw **access card swipe logs** from the company's Access Control Management System (ACMS) into a structured Power BI dashboard. Hence, the creation of a centralized, visual view of their team's attendance behaviour were developed.

---

## 🎯 Business Problem

| Pain Point | Impact |
|---|---|
| No dedicated attendance tracking system | Managers had no reliable data on workforce patterns |
| Raw data locked in security office software | Required manual requests to the security team to obtain any data |
| No visibility into OT utilization | Overtime patterns were unmonitored and unoptimized |
| No absence trend analysis | Resource planning was reactive rather than proactive |
| Headcount monitoring done informally | No single source of truth for shift attendance |

---

## 💡 Solution

Designed and built a **first-of-its-kind attendance analytics dashboard** for the respective department. The pipeline began with a manual extraction of access card entry/exit logs from the ACMS software at the security office, followed by data cleansing and EDA in Excel, and culminated in an interactive Power BI dashboard that gave respective department managers on-demand visibility into their workforce.

---

## 📊 Dashboard Features

- **Shift Attendance Tracking** — Monitor which employees were present for each shift, with entry and exit timestamps from security gate swipes
- **Overtime (OT) Utilization** — Track OT patterns across the team to identify trends and manage workload distribution
- **Absence & Leave Trends** — Visualize absence frequency and patterns over time to support proactive planning
- **Late Arrival / Early Departure Monitoring** — Flag attendance anomalies based on expected shift hours
- **Headcount Overview** — Real-time team headcount visibility across shifts and time periods

---

## 🔄 Data Pipeline Architecture

```
[ACMS Software — Security Office]
  • Access card swipe logs
  • Entry & exit timestamps per employee
  • Manually requested & exported
      │
      ▼
[Excel — Data Cleansing & EDA]
  • Removed duplicates & detect inconsistencies
  • Structured raw swipe data into shift records
  • Calculated OT hours, absence flags, late arrivals
  • Exploratory analysis to identify patterns
      │
      ▼
[Power BI Dashboard]
  • Interactive attendance analytics
  • Drill-down by employee
  • Used by the respective department managers for resource planning
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Access Control Management System (ACMS)** | Source system — access card entry/exit data extraction |
| **Microsoft Excel** | Data cleansing, structuring, and Exploratory Data Analysis (EDA) |
| **Microsoft Power BI** | Interactive dashboard & workforce analytics visualization |

---

## 📈 Results & Impact

| Metric | Result |
|---|---|
| 🆕 First system of its kind | **Zero** attendance tracking tools existed within the respective department before this project |
| 👁️ Visibility created | Respective department managers gained **full workforce attendance oversight** for the first time |
| 📊 Metrics tracked | Attendance, OT, absences, late arrivals  — **all in one place** |
| 🗂️ Data previously inaccessible | Raw logs were siloed in the security office with no analytical layer |

---

## 👥 Stakeholder Impact

| Role | How They Used the Dashboard |
|---|---|
| **Department Managers** | Monitored shift attendance, tracked OT utilization, identified absence trends, and made informed decisions on team resource planning |

---

## 📁 Repository Structure

```
employee-attendance-powerbi-dashboard/
│
├── README.md                   ← You are here
├── dashboard.pbix              ← Power BI report file (sanitized)
└── assets/
    └── dashboard_preview.png   ← Dashboard screenshot
```

> ⚠️ **Note:** All data in this repository has been fully sanitized. Employee names, access card IDs, timestamps, and any personally identifiable information (PII) have been replaced with anonymized dummy data from **Kaggle.com** to protect employee privacy and company confidentiality.

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/fareirfan/employee-attendance-powerbi-dashboard.git
   ```

2. **Open `dashboard.pbix`** in Microsoft Power BI Desktop to explore the report

---

## 👤 About the Author

**Fariez Eirfan** — Aspiring Data Analyst with a background in Mechanical Engineering (UTM). Passionate about turning raw operational data into actionable insights that drive real business decisions.

🔗 [LinkedIn](https://www.linkedin.com/in/fariezeirfan)

---

*Built during an apprenticeship program at Celestica Electronics (M) Sdn Bhd*
