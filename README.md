# 👥 HR Workforce Analytics Dashboard | Power BI

## 📊 Project Overview

The **HR Workforce Analytics Dashboard** is an interactive Power BI project designed to provide comprehensive insights into workforce structure, employee attrition, compensation, hiring trends, training investment, and employee performance.

The project consists of three interactive dashboard pages:

1. 🏢 **Workforce Overview**
2. 📉 **Attrition Analysis**
3. 💰 **Compensation & Training Analysis**

This dashboard helps HR teams and management understand workforce trends and make data-driven decisions related to employee retention, compensation, hiring, and performance.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze total and active employee headcount
- Measure employee attrition and termination trends
- Analyze hiring trends year-over-year
- Understand workforce distribution by career level
- Compare average salaries across departments
- Analyze salary bands and salary benchmarking
- Evaluate training investment by department
- Identify high-performing employees and departments
- Analyze employee tenure
- Understand performance distribution across departments
- Provide an interactive HR decision-making dashboard

---

# 📌 Dashboard Pages

<p align = "center">
 <image src = "(https://github.com/KANISHSINGH1230/HR_DATA_Analytics/blob/main/image/WORKFORCE%20OVERVIEW.png)" widh =
"100%" alt = "workforce">


# "WORKFORCE OVERVIEW.png"


## 1️⃣ Workforce Overview

The Workforce Overview page provides a high-level summary of the organization's workforce.

### Key KPIs

- **Total Headcount:** 50K
- **Active Headcount:** 41K
- **Attrition Rate:** 17.89%
- **Average Salary:** $69.85K
- **Gender Diversity Ratio:** 55.31
- **Total Training Cost:** $27.93M
- **Average Tenure:** 4.69 Years
- **High Performance %:** 23.10%

### Visualizations

- Year-to-Date New Hires by Month
- Average Salary by Department
- Department Salary & Performance Ranking
- Performance Distribution by Department
- Workforce by Career Level Band
- Active Headcount by Department
- Annual Hiring vs Same Period Last Year

### Key Insights

- The organization has approximately **50K employees**.
- Around **41K employees are currently active**.
- Average employee salary is approximately **$69.85K**.
- Average employee tenure is approximately **4.69 years**.
- High-performing employees represent approximately **23.10%** of the workforce.
- Production has the highest active employee headcount.

---

## 2️⃣ Attrition Analysis

The Attrition Analysis page focuses on employee turnover and termination patterns.

### Key KPIs

- **Attrition Rate:** 21%
- **Terminated Employees:** 2K
- **Attrition Rate YTD:** 3.00
- **Attrition Rate %:** 134.18%

### Visualizations

- Attrition Rate by Department Type
- Terminated Employees by Career Level Band
- Year-over-Year New Hire Growth
- Year-to-Date New Hires
- Year-wise Terminated Employee Count

### Key Insights

- **Software Engineering** has the highest attrition rate among departments.
- Production and Sales also show significant attrition levels.
- Most terminated employees belong to the **Mid Level** career band.
- Year-over-year hiring growth shows significant variation across periods.
- The dashboard allows HR teams to identify departments requiring stronger retention strategies.

---

## 3️⃣ Compensation & Training Analysis

This dashboard focuses on employee compensation, salary benchmarking, salary bands, and training investment.

### Key Analysis

- Average Salary by Department
- Department Salary Ranking
- Employee Salary Flag
- Training Cost by Department
- Employee Distribution by Salary Band

### Key Insights

- **Software Engineering** has the highest average salary.
- Software Engineering ranks **#1** in department salary benchmarking.
- Production has the highest training investment.
- The majority of employees fall into the **Medium salary band**.
- Department-level salary comparisons help identify compensation differences across teams.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development & visualization |
| **DAX** | Measures, KPIs & calculations |
| **Power Query** | Data cleaning & transformation |
| **Microsoft Excel** | Data source / preprocessing |
| **GitHub** | Project documentation & version control |

---

# 🧮 DAX Concepts Used

This project uses several important DAX concepts:

- `CALCULATE()`
- `COUNTROWS()`
- `DISTINCTCOUNT()`
- `DIVIDE()`
- `AVERAGE()`
- `AVERAGEX()`
- `SUM()`
- `TOTALYTD()`
- `USERELATIONSHIP()`
- `DATEDIFF()`
- `TODAY()`
- `ALL()`
- `FILTER()`
- `RANKX()`
- `IF()`
- `SWITCH()`

### Time Intelligence

Time-intelligence calculations were used for:

- Year-to-Date New Hires
- YTD Attrition
- Year-over-Year Hiring Growth
- Annual Hiring Comparison

---

# 📊 Data Model

The project uses an HR employee dataset containing information such as:

- Employee ID
- Employee Name
- Department
- Department Type
- Career Level
- Salary
- Hire Date
- Termination Date
- Employee Status
- Performance Rating
- Training Cost
- Gender
- Salary Band

The data was transformed using **Power Query** before building the Power BI data model.

---

# 🎛️ Interactive Filters

The dashboard includes interactive slicers for:

- 📅 Year
- 🏢 Department Type
- 👔 Career Level Band
- 💰 Salary Band

Users can select different combinations of filters to dynamically analyze workforce and HR metrics.

---

# 📈 Business Questions Answered

This dashboard helps answer questions such as:

### Workforce

- How many employees are currently active?
- What is the total workforce size?
- Which department has the highest headcount?
- What is the average employee tenure?

### Attrition

- What is the overall attrition rate?
- Which department has the highest attrition?
- Which career level has the most terminations?
- How is attrition changing over time?

### Compensation

- Which department has the highest average salary?
- How do departments rank based on salary?
- What is the employee distribution across salary bands?

### Training

- Which department receives the highest training investment?
- How much is being spent on employee training?

### Performance

- Which departments have the highest-performing employees?
- What is the performance distribution across departments?
- What percentage of employees are high performers?

---

# 💡 Key Business Insights

Based on the dashboard analysis:

1. **Software Engineering has the highest average salary** among departments.
2. **Production has the largest employee workforce**, making it a major contributor to overall headcount.
3. **Software Engineering shows the highest attrition rate**, indicating a potential employee retention concern.
4. **Mid-level employees account for a significant portion of terminations**, suggesting a need to investigate retention at this career stage.
5. **Production has the highest training investment**, reflecting its large workforce and training requirements.
6. The organization maintains an average employee tenure of approximately **4.69 years**.
7. High-performing employees represent approximately **23.10%** of the workforce.

---

# 📷 Dashboard Preview

## Workforce Overview

![Workforce Overview](WORKFORCE%20OVERVIEW.png)

## Attrition Analysis

![Attrition Analysis](ATTRITION%20ANALYSIS.png)

## Compensation & Training

![Compensation Dashboard](Compensation.png)

---

# 🚀 Project Workflow

```text
Raw HR Data
     ↓
Data Cleaning
     ↓
Power Query Transformation
     ↓
Data Modeling
     ↓
DAX Calculations
     ↓
KPI Development
     ↓
Interactive Visualizations
     ↓
HR Workforce Dashboard
     ↓
Business Insights
