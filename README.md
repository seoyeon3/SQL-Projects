# SQL Projects

## Project 1: Brewery Data Analysis  
[![SQL Code](https://img.shields.io/badge/SQL%20Code-Brewery%20Analysis-blue?style=flat)](https://github.com/seoyeon3/SQL-Projects/blob/main/brewery_data_analysis.sql)

### Overview
Built a structured SQL-based querying system to extract actionable insights from a relational brewery dataset, enabling analysis of market trends, product characteristics, and regional distribution.

### Key Insights
- **Market Trends** – Identified dominant beer styles and evolving preferences  
- **Product Insights** – Analyzed collaboration beers, high-ABV outliers, and low-rated products  
- **Operational Insights** – Detected breweries with limited production and diverse portfolios  
- **Regional Insights** – Identified high-density brewery locations for market analysis  
- **User Querying** – Enabled flexible search (e.g., by style or name) for data exploration  

---

## Project 2: Academic Progress Evaluation System  
[![SQL + Python](https://img.shields.io/badge/SQL%20%2B%20Python-Rule%20Engine-green?style=flat)](https://github.com/seoyeon3/SQL-Projects/tree/main/academic-progress_check_project)

### Overview
Built a rule-based data processing system that evaluates student academic progress by mapping completed courses to program and stream requirements using SQL and Python.

### Problem
Academic data is distributed across multiple relational tables, while graduation requirements involve complex rule-based constraints.  
Manual evaluation of student progress is inefficient and error-prone.

### Approach
- Extracted and structured academic data using SQL  
- Implemented a Python-based rule engine for requirement matching  
- Applied pattern matching for flexible rule definitions  
- Tracked credit (UOC) accumulation with constraint validation  
- Handled edge cases such as failed courses and free electives  

### Outcome
- Generated structured transcripts linking courses to academic requirements  
- Calculated remaining courses and credits for degree completion  
- Automated evaluation of student progress toward graduation  

### Code
- `helpers.sql` – data extraction  
- `rules.py`, `trans.py`, `prog.py` – rule engine and evaluation logic  
