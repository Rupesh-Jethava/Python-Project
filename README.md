# 📌 Project Overview

This project demonstrates how Python, Pandas, and NumPy can be used to analyze and manage employee data and project details, including cost, status, seniority, and resource allocation. The objective was to simulate a real-world HR + Project Management scenario and generate insights for better decision-making.

## 🔹 Steps & Workflow

✅Data Preparation

✅Imported multiple CSV files (project.csv, employee.csv, seniority_level.csv).

✅Cleaned data by handling missing values, formatting issues, and zero costs.

✅Split employee names into First Name / Last Name for better analysis.

✅Data Integration

✅Merged employee, project, and seniority datasets into a consolidated DataFrame.

✅Established relationships between employee roles, seniority levels, and assigned projects.

✅Feature Engineering

✅Added a Bonus column (5% of project cost for finished projects).

✅Adjusted designation levels if projects failed.

✅Updated employee names with prefixes (Mr. / Mrs.) based on gender.

✅Increased designation levels for employees above a certain age threshold.

✅Analysis & Insights

✅Calculated total project cost per employee using groupby.

✅Filtered employees based on city names (e.g., containing “o”).

✅Identified project allocations and tracked budget utilization & status distribution.

## 📊 Key Outcomes

✅Designed a consolidated project DataFrame capturing Project Name, Cost, Status, Seniority, and Employee details.

✅Automated HR logic such as bonuses, demotions/promotions, and seniority adjustments.

✅Provided insights into budget allocation, project success/failure, and employee workload.

✅Created reusable scripts for data cleaning, merging, and reporting.

## 🛠 Tech Stack

✅Python

✅Pandas & NumPy (data cleaning, transformations, calculations)

✅CSV Files as input/output datasets

## 🌟 Learning Highlights

✅Improved skills in data wrangling and data modeling.

✅Applied business rules (bonuses, demotions, promotions) programmatically.

✅Strengthened understanding of groupby, merging, and conditional logic in Pandas.

