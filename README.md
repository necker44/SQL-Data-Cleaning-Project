# SQL Data Cleaning Project
Data cleaning project using mock data in SQL

Project Overview

This project demonstrates a complete data cleaning workflow using MySQL. The objective was to transform a raw dataset into a clean, standardized dataset suitable for reporting, business intelligence, and downstream analytics.

Throughout the project, I applied common SQL data-cleaning techniques that are frequently used by data analysts and business analysts when preparing data for dashboards, reporting, and decision-making.

Objectives
Inspect and understand the raw dataset
Identify and remove duplicate records
Standardize inconsistent data
Handle missing and null values
Clean and format text fields
Convert data into analysis-ready format
Improve overall data quality and consistency
Skills Demonstrated
MySQL
Data Cleaning
Data Validation
Common Table Expressions (CTEs)
Window Functions
String Functions
Date Formatting
Conditional Logic
Data Standardization
Duplicate Detection
NULL Value Handling
Cleaning Process
1. Created a Working Copy

Created a duplicate table to preserve the original dataset before making modifications.

2. Removed Duplicate Records

Used window functions (ROW_NUMBER()) to identify duplicate records based on business-relevant columns and removed unnecessary duplicates.

3. Standardized Data

Cleaned inconsistent values by:

Correcting inconsistent text values
Standardizing industry names
Cleaning country names
Formatting date fields
Improving overall consistency
4. Handled Missing Values
Identified NULL and blank values
Populated missing values where possible
Removed unnecessary empty records
5. Removed Unnecessary Columns

Dropped columns that were no longer needed after the cleaning process to produce a cleaner final dataset.

SQL Concepts Used
SELECT
UPDATE
DELETE
ALTER TABLE
CREATE TABLE
CTEs
Window Functions
ROW_NUMBER()
CASE Statements
IFNULL()
TRIM()
REPLACE()
STR_TO_DATE()
SUBSTRING()
Self Joins
Project Structure
SQL-Data-Cleaning/
│
├── data_cleaning.sql
├── README.md
└── screenshots/
    ├── original_dataset.png
    ├── duplicate_removal.png
    ├── data_standardization.png
    └── final_dataset.png
Screenshots
Original Dataset



Duplicate Identification



Data Cleaning Process



Final Clean Dataset



Key Takeaways

This project strengthened my understanding of practical SQL data-cleaning techniques commonly used in real-world analytics projects. It reinforced the importance of preparing high-quality data before performing reporting, visualization, or predictive analysis.

The workflow demonstrates a repeatable process for transforming raw data into reliable, analysis-ready datasets using MySQL.

Tools Used
MySQL
MySQL Workbench
Git
GitHub
Acknowledgments

This project was completed as part of the SQL Data Cleaning portfolio project created by Alex The Analyst. I recreated the project independently using MySQL to reinforce SQL fundamentals and data-cleaning best practices while building my analytics portfolio.
