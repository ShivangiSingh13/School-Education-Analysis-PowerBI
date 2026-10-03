# 📊 School Education Analysis — Jalandhar (UDISE+ Power BI Dashboard)

A comprehensive **Power BI** dashboard analyzing the school education system in **Jalandhar district**, built on official **UDISE+** (Unified District Information System for Education Plus) data — covering enrollment, teacher profiles, infrastructure, and governance.

![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811)
![Data](https://img.shields.io/badge/Data-UDISE%2B-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Dashboards](#-dashboards)
- [Key Insights](#-key-insights)
- [Data Source](#-data-source)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Future Improvements](#-future-improvements)
- [License](#-license)

---

## 🚀 Overview

This project turns raw UDISE+ government education data for Jalandhar district into a clear, interactive Power BI dashboard — designed to surface patterns in school infrastructure, student enrollment, and teacher distribution that would otherwise be buried across multiple raw data files.

---

## 🔥 Dashboards

The `.pbix` file includes five linked dashboard views:

| Dashboard | Focus |
|---|---|
| **School Overview** | High-level summary of schools across the district |
| **Student Enrollment** | Enrollment trends and distribution across schools |
| **Teacher Profile** | Teacher counts, qualifications, and demographics |
| **Infrastructure Facilities** | Availability of toilets, playgrounds, electricity, internet, etc. |
| **Governance & Support** | Funding allocation and grant utilization |

---

## 🧠 Key Insights

- Total number of schools, teachers, and overall enrollment figures
- Rural vs. Urban education comparison across the district
- Teacher qualification levels and gender ratio
- Infrastructure gaps — specifically toilets, playgrounds, electricity, and internet access
- Funding and grant utilization patterns across schools

---

## 🗂️ Data Source

Data is sourced from **UDISE+** (Unified District Information System for Education Plus), India's official school education data system, filtered to Jalandhar district for the **2024–25** academic year. The repository includes the following raw datasets (zipped):

- `enrolment_data_1_JALANDHAR_2024-25.zip`
- `enrolment_data_2_JALANDHAR_2024-25.zip`
- `facility_data_JALANDHAR_2024-25.zip`
- `profile_data_1_JALANDHAR_2024-25.zip`
- `profile_data_2_JALANDHAR_2024-25.zip`
- `teacher_data_JALANDHAR_2024-25.zip`

---

## 📂 Project Structure

```
School-Education-Analysis-PowerBI/
│
├── ca2.pbix                                   # Power BI dashboard file
├── enrolment_data_1_JALANDHAR_2024-25.zip      # Student enrollment data (part 1)
├── enrolment_data_2_JALANDHAR_2024-25.zip      # Student enrollment data (part 2)
├── facility_data_JALANDHAR_2024-25.zip         # School infrastructure/facility data
├── profile_data_1_JALANDHAR_2024-25.zip        # School profile data (part 1)
├── profile_data_2_JALANDHAR_2024-25.zip        # School profile data (part 2)
├── teacher_data_JALANDHAR_2024-25.zip          # Teacher data
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only)

### Viewing the Dashboard

```bash
git clone https://github.com/ShivangiSingh13/School-Education-Analysis-PowerBI.git
cd School-Education-Analysis-PowerBI
```

1. Open `ca2.pbix` in Power BI Desktop
2. If prompted to locate the underlying data files, extract the relevant `.zip` files and point Power BI to them
3. Explore the five dashboard tabs using the navigation at the bottom/side of the Power BI window

---

## 📌 Future Improvements

- Publish the dashboard to Power BI Service for browser-based viewing (no desktop install required)
- Expand the analysis to additional districts for comparison
- Add year-over-year trend analysis once multiple years of UDISE+ data are available
- Add a written summary report (PDF/slides) highlighting the top findings for non-technical stakeholders

---

## 📄 License

This project is developed for learning and portfolio demonstration purposes. Underlying data is sourced from UDISE+, a public government dataset.
