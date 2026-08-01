# HR Workforce Analytics Dashboard

An interactive multi-page Power BI dashboard analyzing employee attrition, 
workforce demographics, and compensation trends using the IBM HR Analytics 
Employee Attrition dataset.

## 📊 Project Overview
This dashboard helps HR stakeholders understand:
- Overall headcount trends and attrition rate
- Which departments and job roles are most affected by attrition
- How overtime, tenure, job satisfaction, and work-life balance relate to attrition
- Compensation patterns across roles and gender

## 🔑 Key Features
- **5 interconnected report pages**: Executive Summary, Demographics, Attrition 
  Deep-Dive, Compensation & Performance, and a drillthrough Employee Detail page
- **Drillthrough functionality**: Right-click any department to view individual 
  employee-level records
- **Custom page navigation buttons** for seamless UX
- **KPI cards, treemaps, donut charts, bar charts, and scatter plots**

## 🖼️ Screenshots

### Executive Summary
![Executive Summary](screenshots/01_executive_summary.png)

### Demographics
![Demographics](screenshots/02_demographics.png)

### Attrition Deep-Dive
![Attrition Deep-Dive](screenshots/03_attrition_deepdive.png)

### Compensation & Performance
![Compensation](screenshots/04_compensation.png)

### Employee Detail (Drillthrough)
![Employee Detail](screenshots/05_employee_detail_drillthrough.png)

## 📁 Dataset
[IBM HR Analytics Employee Attrition & Performance dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) 
(via Kaggle) — 1,470 employee records with 35 attributes.

## 🛠️ Tools Used
- Power BI Desktop
- DAX (measures for Attrition Rate, Avg Tenure, etc.)
- Power Query (data cleaning/transformation)

## 🚀 How to Use
1. Download `HR_Workforce_Analytics_Dashboard.pbix`
2. Open in Power BI Desktop
3. Explore the interactive report — click nav buttons to switch pages, 
   right-click department bars to drill through to employee-level detail

## 📌 Key Insights
- Overall attrition rate: 16.1%
- Employees working overtime show significantly higher attrition
- Sales department has the highest attrition rate among departments
- Attrition is highest among employees in their first year of tenure
