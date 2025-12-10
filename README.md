# Longitudinal Data Analysis of Housing Supply and Poverty Exposure in the U.S.

## Project Overview
This project looks at how affordable housing availability for low-income households has changed across U.S. states from 2014 to 2023. It also looks at whether housing shortages are associated with higher poxerty exposure. Using state-level averages that were computed from county-level mobility metrics provided by the Urban Institute, I create vizualtions to highlight states with the most servere shortages and linear regression models that test the these relationships. Ultimately, the goal is to address disparities by geographic that may provide as barriers to upward mobility and inform public policy.

## Project Structure
```text
python_final_project/
├── data_raw/  # Raw, unprocessed data files
│   ├── 11_mobility-metrics_county_longitudinal_0.csv  # Overall county-lvl mobility metrics
│   └── 13_mobility-metrics_county_race-share_longitudinal.csv  # Neighborhood racial composition
├── data/  # Cleaned and processed data
│   ├── 11_mobility-metrics_county_longitudinal_0.csv  # (not clean yet)
│   └── 13_mobility-metrics_county_race-share_longitudinal.csv  # (not clean yet)
├── notebook.ipynb  # Main analysis notebook
└── README.md  # This file
```

## Requirements
Python 3.7+
pandas
matplotlib
numpy
jupyter (for local execution)

## Installation and Setup
# Local Execution
1. Clone this repository:
`git clone https://github.com/Adrian1840/MATH120_Final_Project/tree/main
   cd python_final_project`
2. Install required packages (if needed):
`pip install pandas matplotlib numpy jupyter`

3. Launch Jupyter Notebook:
`jupyter notebook notebook.ipynb`

# Google Colab Execution
1. Open Google Colab
2. pload the notebook.ipynb file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment

## Data Description
Sales Data: Contains transaction records with date, product, category, sales amount, region, and customer ID
Customer Data: Contains customer information including name, age, email, and city

## Analysis Features
Data loading and cleaning
Data merging operations
Summary statistics calculation
Sales analysis by category and region
Data visualization with matplotlib
Modular code organization

## Key Learning Objectives Demonstrated
File I/O operations with pandas
Data cleaning and preprocessing
Data merging and joining
Statistical analysis
Data visualization
Function creation and modular programming
Environment compatibility (local vs. cloud)

## Usage
Run all cells in `MATH120_Final_Project (First Draft).ipynb` sequentially. The notebook will:

1. Set up the environment automatically
2. Load and clean the raw data
3. Perform statistical analysis
4. Generate visualizations
5. Save processed data to the `data/` folder

## Author
Adrian Lopez
MATH 120 - Fall/2025
