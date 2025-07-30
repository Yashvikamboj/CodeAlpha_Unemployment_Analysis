## Unemployment Analysis in India using Python

## Project Overview

This project was developed as part of a Data Science internship with **CodeAlpha**.  
It focuses on analyzing regional unemployment trends across India using real-world data.  
The goal is to understand patterns, impacts (including COVID-19), and derive meaningful insights using data visualization.


## Tools & Technologies

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Seaborn  
- Conda Environment (`codealpha_env`)


## Dataset

- Source: Kaggle  
- Format: CSV  
- Contains:  
  - Date  
  - Region (State/UT)  
  - Area Type (Urban/Rural)  
  - Estimated Employment & Unemployment  
  - Unemployment Rate (%)


## Workflow Summary

1. **Environment Setup**  
   Created a virtual environment and installed required Python libraries.

2. **Data Loading & Inspection**  
   Loaded the dataset using `pandas`, inspected rows, columns, missing values.

3. **Data Cleaning & Preparation** 
   - Converted date column to datetime  
   - Renamed columns for readability  
   - Handled missing data  
   - Sorted and structured the dataset

4. **Data Visualization**  
   - Line Chart – Time-wise unemployment trends  
   - Boxplot – State-wise unemployment comparison  
   - Heatmap – Unemployment distribution across months & regions

5. **Insights Derived**  
   - Unemployment spiked during COVID-19 lockdowns  
   - Urban areas were more affected than rural  
   - States like Tripura and Delhi showed higher unemployment rates  
   - Clear seasonal patterns observed


## Key Takeaways

- COVID-19 had a visible impact on employment trends.  
- Regional differences and fluctuations suggest the need for state-specific strategies.  
- Data visualization helps identify patterns that may influence social and economic policies.


## Files Included

- `unemployment_analysis.ipynb` – Jupyter notebook with full analysis  
- `Unemployment in India.csv` – The dataset used for analysis 
- `README.md` – This file

## How to Run

1. Clone or download this repository  
2. Set up a Python environment (e.g., `codealpha_env`)  
3. Install dependencies using `pip install`  
4. Launch Jupyter Notebook and open the `.ipynb` file


## Author

- Name: Yashvi 
- Internship: CodeAlpha  
- Domain: Data Science 

