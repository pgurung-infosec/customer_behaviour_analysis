# customer_behaviour_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL and Power BI

1. Overview

This project demonstrates an end-to-end data analytics workflow, including data extraction, cleaning, analysis, visualization, and reporting.

The objective is to transform raw data into actionable business insights using Python, SQL, and Power BI. The final outputs include a dashboard, analytical report, and presentation summarizing key findings.

Skills Demonstrated

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

SQL querying and aggregations

Dashboard development (Power BI)

Business insight communication

2. Dataset

The dataset contains structured records related to [replace with your dataset: e.g., customer shopping behavior / employee timesheets / sales transactions].

Key Features:

Numerical variables (e.g., sales, age, hours worked)

Categorical variables (e.g., category, department, region)

Date/time fields for trend analysis

The dataset was initially processed in Python and then stored in a relational database for SQL-based analysis.

3. Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	Data cleaning & EDA
PostgreSQL / MySQL / SQL Server	Data storage
SQL	Aggregations, filtering, ranking, joins
Power BI	Interactive dashboard development
Gamma	Presentation creation
Jupyter Notebook	Analysis workflow
4. Project Workflow
Step 1: Data Loading

Imported dataset using Pandas

Reviewed structure, data types, and summary statistics

Step 2: Data Cleaning

Handled missing values

Removed duplicates

Corrected data types

Created derived columns where needed

Step 3: Exploratory Data Analysis (EDA)

Analyzed distributions and trends

Identified key patterns

Performed grouped aggregations

Built supporting visualizations

Step 4: SQL Analysis

Loaded cleaned dataset into relational database

Wrote queries to:

Calculate totals and averages

Rank top-performing categories

Perform joins and filtering

Cross-validated SQL results with Python analysis

Step 5: Dashboard Development

Built interactive Power BI dashboard

Designed KPIs and summary visuals

Added slicers for dynamic filtering

Structured visuals for executive-level readability

Step 6: Reporting & Presentation

Documented findings in a structured report

Created presentation slides summarizing insights and recommendations

5. Dashboard Highlights

The Power BI dashboard includes:

Key Performance Indicators (KPIs)

Category-level performance breakdowns

Time-based trend analysis

Interactive filtering capabilities

Comparative segment analysis

6. Key Insights

Identified top-performing categories and segments

Discovered trends across time periods

Highlighted performance drivers

Provided data-backed recommendations

7. Project Structure
project-folder/
│
├── data/
├── notebooks/
│   └── analysis.ipynb
├── sql/
│   └── queries.sql
├── powerbi/
│   └── dashboard.pbix
├── presentation/
│   └── project_presentation.pptx
└── README.md

8. How to Run

Clone the repository
git clone <repository-link>

Install dependencies
pip install pandas numpy matplotlib seaborn sqlalchemy

Run the notebook
jupyter notebook

Load the cleaned dataset into your SQL database.

Open the Power BI file to view the dashboard.

9. Project Outcome

This project demonstrates the ability to:

Work with real-world datasets

Perform structured data analysis

Write efficient SQL queries

Build executive-level dashboards

Communicate insights clearly
