# Public Safety Data Analysis

## Overview
This project is focused on analyzing various datasets related to Chicago, including crime data, cense information, and public schol safety scores. By leverating  SQL and Python, data manipulation performed, aggregation, and and insights extraction to support data-driven decisions around public safety, commity well-being, and urban planing.


## Datasets
The following datasets are used in this project:
- **Chicago Crime Data**: Contains records of reported crimes in Chicago.
- **Chicago Census Data**: Provides demographic and socio-economic data for comminity areas.
- **Chicago Public Schools Data**: Include information about schools, focusing on safety scores and school types.


## Project Goals
1. **Identify High-Risk Areas**: Find community areas with the highest crime rates.
2. **Analyze Socio-Economic Factors**: Examine the relationship between poverty levels, hardship index, and crime.
3. **School Safety Analysis**: Assess safety scores across different types of schools in Chicago.

## Key Features
- SQL queries to explore and manipulate data in SQLite.
- Python scripts to automate data loading, querying, and reporting.
- Subqueries and complex SQL joins to extract meaningful insights.
- Summary statistics and visualizations to present findings.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/jparep/public-safety-data-analysis.git
   cd public-safety-data-analysis
   ```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Load data into SQLite: Run the load_data.py script to import CSV data into the FinalDB.db SQLite database.
```bash
python scripts/load_data.py
```


## Usage

- **Data Loading**: ```scripts/load_data.py``` – Imports datasets into SQLite.
- **Data Analysis**: Use notebooks in the notebooks/ directory for various analyses, including crime trends, socio-economic impacts, and school safety.
- **Reporting**: Run `scripts/analysis_report.py` to generate summary reports for key insights.