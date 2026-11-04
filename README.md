# Excel Data Analytics Projects

Two Excel projects exploring data job salaries and skill demand through an interactive dashboard and job market analysis.

## 1. Excel Salary Dashboard

An interactive dashboard for exploring salary information across data-related roles, countries, and employment types.

### Features

- Filter results by job title, country, and employment type.
- Display median annual salary, job count, and the most common job posting platform for the selected criteria.
- Compare median salaries across job titles.
- Visualize geographic salary differences with a map chart.

### Techniques Used

- **Conditional calculations:** `MEDIAN`, `IF`, and `COUNTIFS` for calculating metrics under multiple criteria.
- **Lookup functions:** `XLOOKUP` for retrieving results associated with a selected role.
- **Dynamic arrays:** `FILTER`, `SORT`, and `UNIQUE` for generating filtered and sorted lists.
- **Text functions:** `SEARCH` for matching employment types within job records.
- **Data validation:** Drop-down lists for interactive selections.
- **Excel tables:** Structured references for organizing source data and formulas.
- **Charts:** Bar charts and a map chart for salary comparisons.

### Files

- [Raw Data](Excel_Salary_Dashboard/raw_data/)
- [Dashboard Workbook](Excel_Salary_Dashboard/finished_project/)

## 2. Excel Data Jobs Analysis

An analysis of salary differences, skill requirements, and job demand across data-related roles.

### Analysis Questions

1. How does the number of requested skills relate to median salary?
2. How do median salaries differ between US and non-US job postings?
3. Which skills are most frequently requested across data roles?
4. How do median salary and demand compare for commonly requested skills?

### Data Preparation

- Import the source dataset using Power Query.
- Set column data types and clean text fields.
- Remove unnecessary columns.
- Split skill lists into individual job-skill records.
- Organize job information and skill information into related tables.
- Connect the tables through a job identifier.

### Techniques Used

- **Power Query:** Data extraction, cleaning, transformation, and loading.
- **Power Pivot:** Building a relational data model.
- **Table relationships:** Connecting job records with individual skill records.
- **DAX:** Calculating median salaries and metrics under different filter contexts.
- **PivotTables:** Summarizing salaries and skill demand by role, region, and skill.
- **PivotCharts:** Visualizing comparisons from summarized data.
- **Combo charts:** Comparing median salary and skill likelihood using separate axes.

### Files

- [Raw Data](Excel_Data_Jobs_Analysis/raw_data/)
- [Analysis Workbook](Excel_Data_Jobs_Analysis/finished_project/)

## Repository Structure

```text
.
├── README.md
├── LICENSE
├── Excel_Salary_Dashboard/
│   ├── raw_data/
│   └── finished_project/
└── Excel_Data_Jobs_Analysis/
    ├── raw_data/
    └── finished_project/
