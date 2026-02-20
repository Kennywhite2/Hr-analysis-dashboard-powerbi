# HR Analysis Dashboard (Power BI)

End-to-end **HR analytics dashboard** built in **Power BI** using **Excel/CSV** data.  
This project demonstrates the full workflow: **data preparation (Power Query)** → **data modeling** → **DAX measures** → **interactive reporting**.

## 📌 Project Objective
Provide a clear, decision-ready view of workforce health by tracking key HR KPIs such as headcount, attrition, attrition rate, and employee demographics—enabling HR teams to spot trends and take action.

## ✅ What the Dashboard Shows
Key metrics and breakdowns included in the report:
- **Overall Employees (Headcount)**
- **Attrition Count**
- **Attrition Rate**
- **Active Employees**
- **Average Age**
- Department-wise attrition (e.g., R&D, Sales, HR)
- Employee distribution by age group and gender
- Education field-wise attrition
- Job satisfaction rating by job role

## 🧰 Tools & Skills Used
- **Power BI Desktop**
- **Power Query (M)** for data cleaning and transformations
- **DAX** for KPI measures
- **Data Modeling** (relationships, reliable filtering, KPI consistency)
- **Excel / CSV** as the data source

## 🗂 Files in This Repository
- `dashboard/HR_Analysis_Dashboard.pbix` — Power BI report file  
- `dashboard/screenshots/` — dashboard screenshots  
- `data/HR_Data.xlsx` — dataset used (use a sample/anonymized file if needed)  
- `docs/` — documentation (data dictionary, DAX notes)

## 🖼 Dashboard Screenshot
![HR Dashboard Overview](dashboard/screenshots/hr_dashboard_overview.png)

## ▶️ How to Open and Run
1. Download this repository  
2. Open `dashboard/HR_Analysis_Dashboard.pbix` in **Power BI Desktop**  
3. If Power BI asks for the data source path:
   - Go to **Transform data → Data source settings**
   - Change the source path to your local `data/HR_Data.xlsx`

## 📌 Notes / Future Improvements
- Add a dedicated Date table for stronger time intelligence (monthly trends)
- Add drill-through pages (department → role → deeper breakdowns)
- Add cohort-style retention analysis (hire month cohorts)

## 👤 Author
**John Okoye**  
GitHub: https://github.com/Kennywhite2