# housing-prices-analysis

Python data pipeline analyzing 50,000+ housing records across California and Texas, revealing key market trends through automated data processing and an interactive multi-page HTML dashboard.

## Overview
This project processes and analyzes large housing datasets from California and Texas to uncover pricing patterns, demographic trends, and market differences across both states. The analysis revealed that California housing values were approximately 40% higher on average, with significant regional variation across both states.

Key questions explored:
- How do housing prices differ between California and Texas?
- What demographic and economic factors most strongly influence housing value?
- How do racial and economic demographics correlate with housing markets across both states?

## Tech Stack
- Python — data processing and analysis
- Pandas — data cleaning, transformation, and pipeline automation
- Jupyter Notebook — exploratory analysis and data extraction
- HTML/CSS — interactive multi-page dashboard
- Plotly — interactive charts and visualizations
- Exception handling and logging for pipeline reliability

## How to Run

### View the Dashboard
Open `index.html` in your browser to launch the interactive dashboard — no installation required.

### Run the Analysis
1. Clone the repo
2. Install dependencies:
```bash
pip install pandas matplotlib plotly jupyter
```
3. Open and run the data extraction notebook:
```bash
jupyter notebook Group6_FinalProject_DataExtraction.ipynb
```
4. Or run the Python script directly:
```bash
python group6_finalproject_dataextraction.py
```

## Dashboard Pages
The interactive dashboard includes the following pages:
- **index.html** — Main landing page and navigation
- **HousingAspectsPage.html** — Housing price breakdowns and comparisons
- **EconomicPage.html** — Economic indicators and income analysis
- **DemographicsPage.html** — Racial and demographic breakdowns by region

## Visualizations
The dashboard includes 15+ interactive charts including:
- Pie charts — demographic breakdowns for California and Texas
- Bar charts — housing value comparisons across regions
- Histograms — price distribution for California and Texas
- Sunburst charts — hierarchical demographic and housing data
- Box charts — price range and outlier analysis

*(Add screenshots of your dashboard here)*

## Project Structure
```
housing-prices-analysis/
├── index.html                              # Main dashboard entry point
├── HousingAspectsPage.html                 # Housing analysis page
├── EconomicPage.html                       # Economic analysis page
├── DemographicsPage.html                   # Demographics analysis page
├── DataFrames__Project.ipynb               # Main analysis notebook
├── Group6_FinalProject_DataExtraction.ipynb # Data extraction notebook
├── group6_finalproject_dataextraction.py   # Data extraction script
├── California House Information Data.csv   # California housing dataset
├── California Race Data.csv                # California demographics data
├── Consensus_Data_California_2022.csv      # California census data
├── Consensus_Data_Texas_2022.csv           # Texas census data
├── Texas House Information.csv             # Texas housing dataset
├── Texas Race Data.csv                     # Texas demographics data
└── visualizations/                         # Individual chart HTML files
    ├── pieChartCaliforniaViz1.html
    ├── pieChartCaliforniaViz2.html
    ├── pieChartCaliforniaViz3.html
    ├── pieChartTexasViz1.html
    ├── pieChartTexasViz2.html
    ├── pieChartTexasViz3.html
    ├── barChartViz4.html
    ├── barChartViz5.html
    ├── barChartViz8.html
    ├── sunBurstViz6.html
    ├── sunBurstViz7.html
    ├── boxChartViz9.html
    ├── histogramCaliforniaViz10.html
    └── histogramTexasViz10.html
```

## Key Findings
- California housing values averaged ~40% higher than Texas
- Strong correlation between household income and housing prices in both states
- Significant demographic variation across regions within each state
- Automated data cleaning pipeline reduced manual processing time significantly

## Data Sources
- California and Texas housing records — publicly available census and housing data (2022)
- Census demographic data for California and Texas (2022)

## Collaborators
Completed in collaboration with a partner as part of CSE 10001 - Principles of Computing at the University of Notre Dame (Spring 2024).

## Acknowledgements
University of Notre Dame — CSE 10001 Principles of Computing
