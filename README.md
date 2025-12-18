# Longitudinal Data Analysis of Afffordable Housing Supply and Poverty Exposure in the U.S.

## Project Overview
This project looks at how affordable housing availability for low-income households has changed across U.S. states from 2014 to 2023. It also looks at whether housing shortages are associated with higher poverty exposure. Using state-level averages that were computed from county-level mobility metrics provided by the Urban Institute, I create vizualtions to highlight states with the most servere shortages and linear regression models that test these relationships. Ultimately, the goal is to address disparities by geographic that may provide as barriers to upward mobility and inform public policy.

## Project Structure
```text
python_final_project/
├── data_raw/  # Raw, unprocessed data files
│   ├── 11_mobility-metrics_county_longitudinal_0.zip  # Overall county-lvl mobility metrics(too big, zip file)
├── data/  # Cleaned and processed data
│   ├── county_mobility.csv  # (Removed NA vals to make file smaller, not a zip file)
├── notebooks/
│   ├── MATH 120 - Final Written Report.pdf #Written Report
|   ├── MATH120_Final_Project.ipynb # Main analysis notebook
└── README.md  # This file
```

## Requirements
- Python 3.7+
- pandas
- matplotlib
- numpy
- jupyter (for local execution)

## Installation and Setup
### Local Execution
1. Clone this repository:
```text
git clone https://github.com/Adrian1840/MATH120_Final_Project/tree/main
cd python_final_project
```
2. Install required packages (if needed):
```text
pip install pandas matplotlib numpy jupyter
```
4. Launch Jupyter Notebook:
```text
jupyter notebook MATH120_Final_Project.ipynb
```

### Google Colab Execution
1. Open Google Colab
2. Upload the `MATH120_Final_Project.ipynb` file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment

## Data Description
- **County-level mobility metrics** across 2014–2023: Contains variables on housing affordadability/availability, share of poverty exposure, and share of homeless public-school students.
   
## Analysis Features
- Data loading and cleaning
- Data wrangling with real longitudinal indicators
- State-by-year aggregation
- Clear trend visualization using Plotly line charts
- Exploratory association testing using scatterplots with fitted regression lines and simple linear regression (OLS).

## Key Learning Objectives Demonstrated
- File I/O with pandas in a reproducible project structure
- Working with longitudinal county-level and state-level mobility data across multiple years.
- Data grouping and aggregation for state-year summaries
- Exploratory data visualization with Plotly to analyze trends over time and compare states.
- Identification and comparison of states with systematically low affordable housing availability.
- Application of simple linear regression (OLS) to examine associations between affordable housing, poverty exposure, and student homelessness.
- Interpretation of regression outputs in order to inform policy on allocating resources for affordable housing and student homelessness prevention.

## Usage
Run all cells in `MATH120_Final_Project.ipynb` sequentially. The notebook will:

1. Set up the environment automatically
2. Load and clean the raw data
3. Perform statistical analysis
4. Generate visualizations
5. Save processed data to the `data/` folder

## Author
Adrian Lopez
MATH 120 - Fall/2025
