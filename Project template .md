# PyData Capstone Project Proposal Template
Project Title
# Analyzing Early Marriages in Northern Kenya: A Gender-Based Violence Perspective

## Project Summary
This project focuses on early marriages as a form of gender-based violence in Northern Kenya. The dataset includes demographic, socio-economic, and regional data related to girls and young women affected by early marriage. It seeks to uncover patterns, causes, and consequences of early marriages in counties such as Mandera, Wajir, Garissa, Marsabit, and Turkana. By using data analysis and visualization tools, the project aims to deliver actionable insights to policymakers, NGOs, and advocacy groups working to reduce GBV in the region.

## Problem Statement
Early marriage remains a widespread form of gender-based violence in Northern Kenya, often rooted in poverty, cultural norms, and limited access to education. Despite numerous interventions, data gaps and underreporting persist. This project aims to analyze available data to identify high-risk areas, the socio-economic drivers behind early marriages, and affected age groups. The findings will support data-driven policy, community awareness, and targeted GBV prevention programs.

### Link to Dataset(s):
(To be updated – e.g., Kenya DHS, KNBS, NGEC reports, UNICEF datasets)

## Technical Details
### Python Components
Python Version: Python 3.9 or above

### Core Python Concepts to Be Used
Data Types: Lists, Dictionaries, DataFrames for organizing structured data

Control Structures: Loops and Conditional Statements for filtering and logic

Functions: For modular data analysis and cleaning workflows

File Handling: Reading/writing CSVs and Excel files

SQL Integration: Using sqlite3 or SQLAlchemy to query and manage structured GBV data

### Basic Python Libraries
pandas – For data cleaning, wrangling, and analysis

numpy – For handling numerical data and performing calculations

matplotlib / seaborn / plotly – For data visualization

sqlite3 or SQLAlchemy – For storing and querying cleaned datasets

openpyxl or xlrd – For reading Excel sheets if needed

Tableau – For interactive dashboards and stakeholder presentations

### Program Structure
Core Features
Input Handling:

Import data from CSVs, Excel, and SQL databases

Allow updates from cleaned Excel files

Data Preprocessing:

Handle missing values, inconsistent age ranges, duplicate entries

Normalize gender, county names, and socio-economic categories

### Analysis Phase:

Track early marriage rates by county and year

Cross-analyze with education levels, income, and urban/rural classification

Identify trends, correlations, and possible outliers

### Visualization:

Use Python (Seaborn/Plotly) for detailed graphs

Use Tableau for intuitive, interactive dashboards (e.g., maps, bar charts, timelines)

Output:

Generate reports and insights for presentation to stakeholders

Recommend policy actions based on evidence

### Feature 2
Description
In-depth correlation analysis between early marriage rates and variables such as poverty levels, school dropout rates, and geographic isolation.

Python Implementation Approach
Use pandas.merge() and groupby() to aggregate indicators

Use numpy and corr() functions to assess relationships

Visualize with seaborn.heatmap() or Tableau charts

User Interface
Although not a full GUI, the project will use:

Tableau dashboards for visual exploration

Python-generated charts for automated insights

Optional: Jupyter Notebooks with markdown explanations and visuals for stakeholder engagement

## Project Timeline
Phase	Description	Duration
Phase 1	Define scope, gather datasets, set up Python/SQL/Excel environment	1–2 days
Phase 2	Clean and structure data using Excel and Pandas	2 days
Phase 3	Perform exploratory and statistical analysis (Python, SQL)	2 days
Phase 4	Create visualizations in Tableau and Python	2 days
Phase 5	Document findings, test insights, finalize presentation	1–2 days

## Program Design
Modular Structure:

data_loader.py: Import and clean raw data

analysis.py: Perform data analysis and generate insights

visualization.py: Generate graphs and export to Tableau if needed

db_manager.py: Interact with SQL database

## Functions/Classes:

Reusable for loading new data or extending analysis to other GBV forms

Potential Challenges
Data Gaps & Quality:
Inconsistent formats, missing age/gender values, and underreported cases

Regional Coverage:
Some counties may lack consistent yearly data

Bias:
Cultural sensitivity and reporting practices may skew results

Data Integration:
Merging data from multiple sources (surveys, reports, spreadsheets)

## Future Improvements
Predictive Models:
Use ML to predict future early marriage hotspots or risk levels

Interactive Dashboards:
Build with Streamlit or Dash for field worker or policymaker use

Geospatial Insights:
Use GeoPandas or Tableau maps for a clearer geographic representation

Policy Mapping:
Compare data trends with regional policies or NGO activities
