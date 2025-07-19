
# HR Analytics Dashboard (Power BI)
![App Screenshot](https://github.com/Saurabhgupta301/HR-Analytics-Dashboard/blob/main/Template.png?raw=true)

## 📌 Overview
This project implements an end‑to‑end **Human Resources Analytics** dashboard in Power BI. It was developed as part of the Codebasics real‑time challenge set by *Pinali Mandalia* (HR, AtliQ Technologies) to automate key HR reporting tasks.

---

## 🔧 How the Project Was Developed

1. **Data Source**  
   - Utilised the HR dataset from Codebasics YouTube challenge.
   - Included employee details, attendance, feedback, and preferences.

2. **Requirement Gathering**  
   - Work-from-Home (WFH) vs Work-from-Office (WFO) preferences.  
   - Sick leave percentage to monitor employee wellness.  
   - Reasons for frequent WFH.

3. **Data Cleaning & Transformation (Power Query)**  
   - Removed duplicates and nulls, standardized formats.  
   - Merged tables and created custom columns: `Leave Category`, `WFH Reasons`, etc.

4. **Data Modelling**  
   - Star schema: Dimension tables (Employee, Department, Location), Fact tables (Attendance, Feedback).  
   - Proper relationships established (one-to-many), removed circular dependencies.

5. **Measure Creation (DAX)**  
   - Key measures: `Total Sick Leaves %`, `WFH vs WFO %`, `Top Reasons for WFH`, `Engagement Score`.

6. **Dashboard Design**  
   - Created KPI cards, bar/line charts, slicers.  
   - Used filters: Department, Location, Age Group, Tenure.

---

![App Screenshot](https://github.com/Saurabhgupta301/HR-Analytics-Dashboard/blob/main/HR%201.jpg?raw=true)


## ✨ Important Features

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🏠 **Work Preference Analysis**     | WFH vs WFO visual breakdown with drilldowns by department/gender             |
| 💊 **Employee Wellness Tracker**   | Sick-leave % tracker with trend analysis and anomaly detection               |
| 📊 **Reasons for WFH**             | Top reasons visualized (commute, flexibility, personal issues, etc.)         |
| 📅 **Time-Series Trends**         | Monthly WFH/WFO and wellness trends with line graphs                         |
| 🧭 **Interactive Filters**        | Slicers for Department, Age Group, Tenure, and Location                      |
| 🔍 **Insight Cards**             | KPIs for Total Employees, Avg Sick Leave %, and WFH %                        |
| 📥 **HR-Ready Export**            | Dashboards ready for export to reports and presentations                     |

---

## 🎯 Final Outcome
The dashboard streamlines HR reporting, reducing manual Excel work and enabling **data-driven decisions** regarding employee wellness, hybrid policies, and workforce planning.

---

> ✅ *Feel free to fork this repository, add screenshots, or contribute enhancements!*
