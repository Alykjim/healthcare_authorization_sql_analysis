# healthcare_authorization_sql_analysis
SQL project analyzing healthcare authorization data, including turnaround time (TAT), approval vs denial patterns, and utilization trends using SQLite and Jupyter Notebook.

# Healthcare Authorization SQL Analysis

This project analyzes synthetic healthcare authorization data using SQL in Jupyter Notebook. It demonstrates intermediate SQL skills and models real utilization management (UM) workflows.

## Overview
The dataset includes:
- **Members**
- **Procedures (CPT codes)**
- **Authorization requests**

The analysis focuses on:
- Approval vs denial patterns  
- Turnaround time (TAT)  
- Procedure category trends  
- Basic utilization insights  

## SQL Skills Demonstrated
- Creating relational tables  
- Inserting synthetic data  
- JOINs across multiple tables  
- GROUP BY + aggregate functions  
- Date calculations using `julianday()`  
- Sorting and filtering  

## Key Insights
- Imaging procedures had the longest TAT.  
- Physical Therapy showed higher denial rates.  
- Primary Care visits were approved quickly.  
- Texas members generated the most requests.  

## How to Run
Open the notebook and run each cell in order.  
SQLite is created directly inside the notebook—no external files needed.

## Future Enhancements
- Add denial reasons  
- Add claims cost data  
- Use CTEs and window functions  
- Add visualizations for TAT and denial trends  
