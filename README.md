# 👥 HR Analytics Dashboard | Excel

## 📌 Project Overview

This project presents an interactive HR Analytics Dashboard built in Microsoft Excel using a synthetic dataset of 3,000 employee records.

The dashboard analyzes workforce composition, employee exits, attrition trends and compensation patterns to help HR teams understand workforce dynamics and support data-driven decision-making.

The project demonstrates practical skills in:

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- PivotCharts
- Data Cleaning
- Data Modeling
- HR Analytics
- KPI Development
- Interactive Dashboard Design
- Business Analysis

> **Disclaimer:** This project uses synthetic employee data created for portfolio and learning purposes. The figures and insights do not represent an actual organization.

---

## 📊 Dataset

The analysis contains:

- 3,000 Employees
- 2,498 Active Employees
- 502 Exited Employees
- 10 Departments
- Multiple Locations
- Employee records covering 2019–2026

Key fields include:

- Employee ID
- Employee Name
- Gender
- Date of Birth
- Age
- Age Group
- Department
- Job Title
- Location
- Employment Type
- Date of Joining
- Date of Exit
- Employment Status
- Exit Reason
- Annual Salary
- Performance Rating
- Experience
- Education
- Manager
- Recruitment Source
- Work Mode
- Tenure

---

# 📈 Dashboard Pages

## 1. Workforce Analytics

Provides an executive view of the organization's workforce and hiring activity.

### KPIs

- Total Employees — 3,000
- Active Employees — 2,498
- Exited Employees — 502
- 2026 YTD Attrition Rate — 6.47%
- Average Salary — ₹10.55L
- New Hires 2026 — 272

### Analysis

- Active Headcount by Department
- Active Workforce by Location
- Workforce by Gender
- Exits by Department
- Hiring Trend from 2019–2026

This page provides an overview of current workforce composition while also tracking historical hiring and employee movement.

---

## 2. Attrition Analytics

Analyzes employee exits and identifies patterns associated with employee turnover.

### KPIs

- Total Employees — 3,000
- Total Exits — 502
- Overall Exit Percentage — 16.73%
- Average Exit Salary — ₹10.43L

### Analysis

- Employee Exit Trend
- Exit Reasons
- Exits by Department
- Exits by Performance Rating
- Exits by Tenure
- Exits by Age Group

### Key Attrition Observation

Approximately 74% of recorded employee exits occurred within the first three years of tenure:

- <1 Year — 37.65%
- 1–3 Years — 36.25%

Better Opportunity was the most commonly recorded exit reason, followed by Career Growth and Compensation.

> Exit distributions identify where exits are concentrated. They should not automatically be interpreted as group-specific attrition rates without the corresponding employee population denominator.

---

## 3. Compensation Analytics

Analyzes salary distribution and compensation patterns across the active workforce.

### KPIs

- Average Active Salary — ₹10.57L
- Median Active Salary — ₹10.40L
- Top Performer Average Salary — ₹10.34L
- Average Performance Rating — 3.2

### Analysis

- Average Salary by Department
- Salary Distribution
- Performance Rating Distribution
- Average Salary by Experience
- Average Salary by Performance Rating
- Top 10 Job Titles by Average Salary

### Compensation Observation

Higher performance ratings did not automatically correspond to higher average salaries in the synthetic dataset.

This suggests that compensation patterns may also be associated with factors such as job role, department and employee experience.

The analysis demonstrates why salary decisions should be examined across multiple workforce dimensions rather than performance ratings alone.

---

# 🔎 Key Portfolio Insights

Several notable observations emerged from the synthetic dataset:

- 2,498 of 3,000 employees were active.
- 502 employee exits were recorded across the historical dataset.
- 2026 YTD attrition was approximately 6.47%.
- 272 employees joined during 2026 YTD.
- Approximately 74% of exits occurred within the first three years of tenure.
- Better Opportunity accounted for approximately 30.88% of recorded exits.
- Career Growth accounted for approximately 17.73%.
- Compensation accounted for approximately 12.75%.
- Customer Support recorded the highest number of exits, followed by Sales and Procurement.
- Average active employee salary was approximately ₹10.57L.
- Higher performance ratings did not consistently correspond with higher average salaries.

These findings describe this synthetic workforce and should not be interpreted as actual company workforce statistics.

---

# 🛠️ Tools & Techniques

## Microsoft Excel

- PivotTables
- PivotCharts
- Slicers
- Interactive Dashboard Navigation
- Custom Number Formatting
- Conditional Formatting
- Advanced Excel Analysis

## Power Query

Used for:

- Data cleaning
- Data type transformation
- Data preparation
- Standardization
- Refreshable data workflows

## Power Pivot

Used to build the analytical data model and support calculations across workforce, attrition and compensation analysis.

## DAX

Used for business calculations and HR KPIs including:

- Total Employees
- Active Employees
- Exited Employees
- New Hires
- Attrition Rate
- Overall Exit Percentage
- Average Salary
- Median Salary
- Average Exit Salary
- Performance-based Salary Analysis
- Salary Bands

---

# 📐 Selected KPI Logic

### Total Employees

Total distinct employee records.

### Active Employees

Employees whose current Employment Status is Active.

### Exited Employees

Employees whose Employment Status is Exited.

### 2026 YTD Attrition Rate

Calculated using employee exits during 2026 relative to average workforce headcount.

2026 figures:

- Beginning Headcount: 2,384
- New Hires: 272
- Exits: 158
- Current Headcount: 2,498
- Average Headcount: 2,441
- YTD Attrition Rate: 6.47%

### Overall Exit Percentage

502 historical exits divided by 3,000 employee records:

**16.73%**

This metric is presented as Overall Exit Percentage rather than an annual attrition rate.

---

# 🎛️ Interactive Filters

The dashboard allows users to dynamically explore workforce data using slicers such as:

- Department
- Location
- Gender
- Employment Status
- Year
- Age Group
- Performance Rating
- Other relevant workforce dimensions

---

# 📁 Project Structure

HR-Analytics-Excel-Dashboard/
│
├── README.md
│
├── Dashboard/
│   └── HR_Analytics_Excel_Dashboard.xlsx
│
├── Data/
│   ├── HR_Analytics_3000_Employees.csv
│   └── HR_Analytics_Data_Dictionary.csv
│
└── Images/
    ├── HR_Workforce_Analytics.png
    ├── HR_Attrition_Analytics.png
    ├── HR_Compensation_Analytics.png
    └── HR_Analytics_Dashboard_Collage.png

---

# 🎯 Project Objective

The objective of this project was to transform raw employee-level HR data into an interactive HR analytics solution that enables decision-makers to evaluate:

- Workforce composition
- Headcount
- Hiring activity
- Employee exits
- Attrition patterns
- Tenure-related exit patterns
- Department-level workforce movement
- Compensation distribution
- Performance and salary patterns

The project demonstrates how HR data can be transformed into business insights using Excel-based analytics tools.

---

# 💼 Business Questions Addressed

The dashboard was designed to answer questions such as:

1. What does the current workforce look like?
2. Which departments and locations have the largest active workforce?
3. How has hiring changed over time?
4. What are the most frequently recorded reasons for employee exits?
5. At what tenure stage are exits most concentrated?
6. Which departments record the largest number of exits?
7. How is compensation distributed across the organization?
8. How does average salary vary by department, job title and experience?
9. Is higher performance rating consistently associated with higher salary?

---

## 👤 Author

**Harshit Kumar Tiwary**
HR Analytics | Data Analytics | Excel | Power BI | SQL
