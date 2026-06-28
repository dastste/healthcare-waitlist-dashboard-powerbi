# Healthcare Patient Wait List Dashboard | Power BI

![Dashboard Overview](assets/Summary.png)

## Project Overview

This project presents an interactive **Healthcare Patient Wait List Dashboard** built using **Microsoft Power BI**. The dashboard analyses patient wait list performance across specialties, case types, age groups, and waiting time bands between **2018 and 2021**.

The report transforms raw healthcare data into an interactive dashboard that enables users to monitor key performance indicators (KPIs), analyse monthly trends, compare specialties, and explore patient waiting lists through dynamic filtering and drill-down analysis.

---

## Business Questions

The dashboard was developed to answer the following business questions:

1. How has the patient wait list changed over time?
2. Which specialties have the highest patient wait lists?
3. How do Outpatient, Inpatient and Day Case waiting lists compare?
4. Which age groups contribute the most to the overall wait list?
5. How are patients distributed across different waiting time bands?
6. How do Average and Median wait list values compare?

---

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modelling
- CSV Data Sources

---

## Power BI Skills Demonstrated

- Data Cleaning using Power Query
- Data Transformation
- Data Modelling
- DAX Measures
- Calculated Columns
- KPI Cards
- Interactive Slicers
- Matrix Drill-Down Hierarchy
- Report Page Tooltips
- Dynamic Measure Selection (Average / Median)
- Cross-filtering
- Card Visuals
- Matrix Visuals
- Line Charts
- Donut Charts
- Stacked Column Charts
- Dashboard Design

---

## Interactive Features

- Dynamic Average / Median calculation selector
- Archive Date filtering
- Case Type filtering
- Specialty filtering
- Age Profile filtering
- Waiting Time Band filtering
- Matrix Drill-Down hierarchy
- Report Page Tooltips
- Cross-filtering between visuals
- Multi-page dashboard navigation

---

## Dashboard Pages

### Executive Summary

Provides an overview of patient wait list performance using KPI cards, monthly trend analysis, specialty comparisons, and demographic breakdowns.

![Summary Dashboard](assets/Summary.png)

---

### Detailed Analysis

Allows users to drill down into patient wait list data by Archive Month, Specialty, Age Profile, and Waiting Time Band using an interactive matrix.

![Detailed View](assets/Detail.png)

---

### Specialty Analysis

Displays total patient wait lists across specialties to identify areas with the highest patient demand.

![Specialty Analysis](assets/Specialty.png)

---

### Report Page Tooltip

Hovering over the Monthly Trend Analysis visual displays a custom report page tooltip with additional insights without leaving the dashboard.

![Tooltip](assets/tooltip.png)

---

## Key Insights

- Outpatient services account for the largest proportion of the overall patient wait list.
- Patient demand varies significantly across medical specialties.
- Waiting list performance can be analysed by case type, age profile, and waiting time bands.
- Dynamic Average and Median calculations provide different perspectives on patient wait list performance.
- Interactive filtering enables users to explore healthcare data from multiple business perspectives.

---

## Repository Structure

```text
healthcare-waitlist-dashboard-powerbi/
│
├── README.md
├── HealthcareProject.pbix
│
├── assets/
│   ├── Summary.png
│   ├── Detail.png
│   ├── Specialty.png
│   └── tooltip.png
│
└── dataset/
    ├── In_WL_2018.csv
    ├── In_WL_2019.csv
    ├── In_WL_2020.csv
    ├── In_WL_2021.csv
    ├── Op_WL_2018.csv
    ├── Op_WL_2019.csv
    ├── Op_WL_2020.csv
    ├── Op_WL_2021.csv
    └── Mapping_Specialty.csv
```

---

## How to Review the Project

1. Download the repository.
2. Open `HealthcareProject.pbix` using Microsoft Power BI Desktop.
3. Refresh the data if prompted.
4. Explore the dashboard using the interactive slicers.
5. Switch between **Average** and **Median** using the Calculation Method slicer.
6. Hover over the Monthly Trend Analysis chart to view additional insights through report page tooltips.
7. Drill down into the matrix hierarchy for detailed patient wait list analysis.

---

## Key Learning Outcomes

This project strengthened my ability to:

- Build interactive dashboards in Microsoft Power BI.
- Transform and clean healthcare data using Power Query.
- Create reusable DAX measures and calculated columns.
- Design user-friendly business intelligence dashboards.
- Implement drill-down hierarchies and report page tooltips.
- Translate business questions into interactive reporting solutions.

---

## Author

**Toyeeb Abayomi Olayiwola**

Aspiring Data Analyst

**Skills:** SQL | Power BI | Excel
