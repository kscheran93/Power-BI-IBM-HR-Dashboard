# IBM HR Analytics Dashboard

## Overview

This project leverages the IBM HR Analytics Attrition dataset to create a comprehensive Power BI dashboard. The dashboard provides insights into various employee metrics, such as gender distribution, age, hourly rate, job role, education field, department, marital status, and business travel frequency. The objective is to analyze these factors to help stakeholders understand the workforce distribution and identify potential areas of concern, such as attrition risks or imbalances in certain categories.

## Snapshot of Dashboard

![Dashboard_Snapshot](https://github.com/kscheran93/Power-BI-IBM-HR-Dashboard/blob/main/IBM_logo.svg.png)

### Dashboard Link: [Power BI Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiYWMwYmQyMGMtNTMxNy00YWU5LWJkNTUtN2UxYmQ3MTA4NjI1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Problem Statement

The IBM HR Analytics dashboard is designed to offer key insights into employee demographics and other attributes. By visualizing factors like age, gender, job role, and business travel, the dashboard aids in understanding employee distribution and identifying patterns that may influence workforce management decisions. This analysis is crucial for HR departments aiming to improve employee retention, optimize workforce diversity, and enhance overall organizational effectiveness.

## Data Sources

The dataset used in this project is sourced from Kaggle and includes detailed employee data, such as demographics, job roles, compensation, and more.

### Dataset Link: [Kaggle - IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Steps Followed

- **Step 1:** Imported the dataset into Power BI Desktop.
- **Step 2:** Cleaned and prepared the data using Power Query Editor, ensuring data integrity by handling missing or erroneous values.
- **Step 3:** Created visualizations to explore different aspects of the employee data:
  - **Doughnut Chart:** Visualizes the distribution of employees by gender.
    - **Legend:** `gender`
    - **Values:** Sum of `employeeCount`
  - **Clustered Column Chart:** Displays the distribution of employees by age.
    - **X-Axis:** `Age`
    - **Y-Axis:** Sum of `employeeCount`
  - **Clustered Column Chart:** Shows the distribution of employees by hourly rate.
    - **X-Axis:** `HourlyRate`
    - **Y-Axis:** Sum of `employeeCount`
  - **Clustered Bar Chart:** Illustrates the distribution of employees by job role.
    - **Y-Axis:** `JobRole`
    - **X-Axis:** Sum of `employeeCount`
  - **Clustered Bar Chart:** Displays the distribution of employees by education field.
    - **Y-Axis:** `education`
    - **X-Axis:** Sum of `employeeCount`
  - **Clustered Column Chart:** Shows the distribution of employees by department.
    - **Y-Axis:** `department`
    - **X-Axis:** Sum of `employeeCount`
  - **Doughnut Chart:** Visualizes the distribution of employees by marital status.
    - **Legend:** `MartialStatus`
    - **Values:** Sum of `employeeCount`
  - **Clustered Column Chart:** Highlights the distribution of employees by business travel frequency.
    - **Y-Axis:** `BusinessTravel`
    - **X-Axis:** Sum of `employeeCount`
- **Step 4:** Added text boxes and titles to provide context and improve the overall understanding of the data.
- **Step 5:** Designed and formatted the dashboard with a user-friendly layout, ensuring that the visualizations are easy to interpret.
- **Step 6:** Published the dashboard to Power BI Service for sharing with stakeholders and broader accessibility.

## Insights

The IBM HR Analytics dashboard reveals several key insights into the employee data:

### [1] Employees by Gender
   - The doughnut chart shows the gender distribution, which can be used to assess gender diversity within the organization.

### [2] Employees by Age
   - The clustered column chart displays the distribution of employees by age, providing insights into the age demographics of the workforce.

### [3] Employees by Hourly Rate
   - The clustered column chart shows how employees are distributed across different hourly rates, which can highlight compensation trends.

### [4] Employees by Job Role
   - The horizontal bar chart provides an overview of how employees are distributed across various job roles within the organization.

### [5] Employees by Education Field
   - The horizontal bar chart reveals the distribution of employees based on their educational background, helping to understand the diversity of skills and expertise.

### [6] Employees by Department
   - The vertical bar chart highlights the distribution of employees across different departments, indicating the size and structure of each department.

### [7] Employees by Marital Status
   - The doughnut chart visualizes the marital status of employees, which can be relevant for understanding personal demographics.

### [8] Employees by Business Travel
   - The vertical bar chart shows how frequently employees travel for business, which could be linked to job roles or departments that require more travel.

## Conclusion

This IBM HR Analytics Power BI dashboard provides valuable insights into the workforce, helping HR teams and management make data-driven decisions regarding employee retention, diversity, and resource allocation. By understanding these employee attributes, organizations can improve their workforce planning and overall HR strategies.
