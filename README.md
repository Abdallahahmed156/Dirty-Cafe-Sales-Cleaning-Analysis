#  Dirty Cafe Sales: Data Cleaning & Analysis Pipeline

## Project Overview
This project demonstrates an end-to-end data cleaning and exploratory data analysis (EDA) pipeline for a café sales dataset.
The goal was to transform "dirty" raw data into a reliable format for business intelligence.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Visualizations), NumPy (Array operations)

## Data Cleaning Highlights
- **Imputation:** Logical imputation for missing values in `Location` and `Payment Method`.
- **Outlier Analysis:** Validated high-value transactions to ensure business logic consistency.
- **Data Standardization:** Converted date formats and handled categorical errors (e.g., 'Error', 'Unknown').

## Key Insights (EDA)
- Identified top-performing products and revenue share by location.
- Analyzed customer payment behavior after data refinement.
- Seasonal trend analysis using monthly sales growth.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas seaborn matplotlib`.
3. Run the Jupyter Notebook to see the step-by-step cleaning process.
