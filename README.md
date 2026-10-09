# PowerBI-Employee-Analytics-Dashboard
Interactive Employee Analytics Dashboard built with Power BI, Power Query, and DAX to analyze workforce, salary, experience, demographics, and recruitment trends.

#  Employee Analytics Dashboard – Power BI

An interactive Employee Analytics dashboard developed using Power BI to analyze
workforce distribution, salary trends, employee experience and recruitment patterns.

##  Project Overview

This project demonstrates how raw employee data can be transformed into
meaningful business insights using Power BI, Power Query and DAX.

The dashboard provides analysis across:

- Workforce
- Salary
- Experience
- Gender
- Location
- Recruitment trends
- Employee status

##  Business Questions

The dashboard was designed to answer questions such as:

1. How many employees are in the organization?
2. How many employees are currently active?
3. Which department has the highest employee count?
4. Which location has the highest employee concentration?
5. What is the average salary?
6. What is the maximum salary?
7. Which department has the highest average salary?
8. How are employees distributed by experience?
9. How are employees distributed by gender?
10. How many employees joined each year?
11. What is the salary distribution across employees?

---

##  Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel / CSV
- Data Visualization
- Data Cleaning
- Exploratory Data Analysis

---

## Data Preparation

The dataset was cleaned and transformed using Power Query.

Steps included:

- Data type validation
- Duplicate checking
- Null value checking
- Text cleaning
- Date transformation
- Creating calculated columns
- Creating salary and experience bands

---

##  Dashboard Components

### KPI Cards

- Total Employees
- Active Employees
- Average Salary
- Maximum Salary
- Average Experience

### Visualizations

- Employees by Department
- Average Salary by Department
- Employees by Gender
- Employees by Location
- Experience Distribution
- Employees Joined Over Time
- Salary Distribution

### Filters

The dashboard includes interactive filters for:

- Department
- Location
- Gender
- Status
- Experience Band
- Joining Year

---

##  DAX Measures

### Total Employees

```DAX
Total Employees =
COUNTROWS(Employees)
