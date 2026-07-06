# SQL Data Cleaning & Exploratory Data Analysis (EDA) Project (MySQL)

## Project Overview

This project demonstrates a complete SQL analytics workflow using **MySQL**, beginning with raw data cleaning and progressing into exploratory data analysis (EDA).

The objective was to transform an unstructured dataset into a clean, analysis-ready format and then use SQL to uncover trends, patterns, and business insights through exploratory analysis.

This project highlights practical SQL techniques commonly used by Data Analysts, Business Analysts, and Sales Operations professionals to prepare data and support data-driven decision making.

---

# Project Workflow

### Phase 1 – Data Cleaning

Prepared the raw dataset by improving data quality and consistency.

Tasks completed:

* Created a working copy of the original dataset
* Identified and removed duplicate records
* Standardized inconsistent values
* Formatted date fields
* Handled NULL and blank values
* Removed unnecessary columns
* Produced a clean dataset for analysis

---

### Phase 2 – Exploratory Data Analysis (EDA)

After cleaning the data, SQL queries were used to explore the dataset and identify meaningful trends.

Examples of analyses included:

* Total companies by industry
* Geographic distribution of companies
* Layoffs by country
* Layoffs by company
* Layoffs by year
* Layoffs by month
* Companies with the largest workforce reductions
* Industries most impacted
* Rolling monthly layoffs
* Company rankings using window functions
* Trend identification over time

---

# Skills Demonstrated

### SQL

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* HAVING
* LIMIT
* Aggregate Functions

### Data Cleaning

* UPDATE
* DELETE
* ALTER TABLE
* NULL Handling
* Data Standardization
* String Functions
* Date Formatting

### Advanced SQL

* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* DENSE_RANK()
* PARTITION BY
* Rolling Totals
* Self Joins
* CASE Statements

### Data Analysis

* Trend Analysis
* Time Series Analysis
* Business Insight Generation
* Ranking & Segmentation
* Aggregation
* KPI Identification

---

# Repository Structure

```text
SQL-Data-Cleaning-EDA/
│
├── Data_Cleaning.sql
├── Exploratory_Data_Analysis.sql
├── README.md
│
└── screenshots/
    ├── original_dataset.png
    ├── duplicate_removal.png
    ├── cleaned_dataset.png
    ├── layoffs_by_company.png
    ├── layoffs_by_industry.png
    ├── rolling_total.png
    └── yearly_trends.png
```

---

# Project Highlights

## Data Cleaning

✔ Removed duplicate records

✔ Standardized inconsistent values

✔ Corrected date formatting

✔ Handled missing data

✔ Removed unnecessary fields

✔ Created an analysis-ready dataset

---

## Exploratory Data Analysis

Key business questions answered include:

* Which companies experienced the largest layoffs?
* Which industries were impacted the most?
* Which countries had the highest number of layoffs?
* How did layoffs change over time?
* Which years experienced the highest workforce reductions?
* What monthly trends emerged?
* Which companies ranked highest within each year for layoffs?
* What cumulative trends appeared throughout the dataset?

---

# Business Value

This project demonstrates how SQL can be used throughout the analytics lifecycle:

* Prepare messy, real-world datasets
* Improve data quality
* Explore trends and patterns
* Generate business insights
* Support strategic decision making using data

---

# Tools Used

* MySQL
* MySQL Workbench
* Git
* GitHub

---


# What I Learned

This project strengthened my understanding of writing efficient SQL queries to clean and analyze data. It reinforced the importance of data quality before analysis and provided hands-on experience using SQL to generate meaningful business insights.

Through this project, I gained additional experience with:

* Data transformation
* Exploratory data analysis
* Window functions
* Ranking techniques
* Time-series analysis
* Aggregations
* Analytical problem solving

---

# Future Improvements

Potential enhancements include:

* Build an interactive Power BI dashboard using the cleaned dataset
* Create Tableau visualizations
* Develop additional KPI reporting
* Perform predictive analysis using Python
* Compare SQL results with Python (Pandas)

---

# Acknowledgments

This project was completed by following the SQL portfolio project created by **Alex The Analyst**. I independently recreated the workflow in MySQL to strengthen my SQL skills and expand my data analytics portfolio while reinforcing best practices for data cleaning and exploratory data analysis.
