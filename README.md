# HR Analytics Dashboard

<p align="center">
  <img src="HR_Analysis Dashboard.png" alt="HR Analytics Dashboard" width="100%">
</p>

<p align="center">
  <b>Power BI • HR Analytics • Employee Attrition • Business Intelligence</b>
</p>

---

## Overview

This project is an interactive **HR Analytics Dashboard** built in **Microsoft Power BI** to analyze employee attrition, workforce demographics, salary distribution, job roles, and tenure patterns.

The dashboard is designed to help HR teams and business leaders identify retention risks, understand workforce trends, and make data-driven decisions to improve employee retention and organizational performance.

---

## Business Problem

Employee attrition directly impacts recruitment cost, productivity, and team stability.  
This dashboard helps answer questions such as:

- Which employee groups are leaving the organization most often?
- Does attrition vary by age, salary, education, or job role?
- Which departments and job roles are most affected?
- How does tenure influence retention?

---

## Key Metrics

| KPI | Value |
|---|---:|
| Total Employees | 1.413K |
| Attrition Count | 210 |
| Attrition Rate | 14.9% |
| Average Age | 38 |
| Average Salary | 6.7K |
| Average Years at Company | 7 |

---

## Dashboard Features

### Attrition by Education
Analyzes turnover by educational background:
- Life Sciences
- Medical
- Marketing
- Technical Degree
- Other fields

### Attrition by Age
Shows how attrition is distributed across age bands:
- 18–25
- 26–35
- 36–45
- 46–55
- 55+

### Attrition by Gender
Compares attrition across male and female employees.

### Attrition by Salary Slab
Highlights the relationship between salary range and employee turnover.

### Attrition by Years at Company
Tracks attrition based on employee tenure.

### Attrition by Job Role
Identifies the roles with the highest attrition, including:
- Sales Executive
- Laboratory Technician
- Research Scientist
- Sales Representative
- Human Resources

---

## Key Insights

- Employees in the **26–35 age group** show the highest attrition.
- Lower salary slabs have a much higher turnover rate.
- **Sales Executive** and **Laboratory Technician** roles experience the most attrition.
- Employees with fewer years at the company are more likely to leave.
- Attrition is concentrated in a few high-risk workforce segments.

---

## Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Microsoft Excel**

---

## Data Preparation

The dataset was cleaned and prepared using Power Query and data modeling techniques:
- Removed inconsistencies
- Standardized columns
- Converted data types
- Created calculated measures
- Built interactive relationships for reporting

---

## DAX Measures

## License

This project is shared for educational and portfolio purposes.

```DAX
Employee Count = COUNT(HR_Analytics[EmployeeNumber])
