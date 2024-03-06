# COVID-19 and Temperature Analysis

This repository contains Python code for analyzing the relationship between COVID-19 cases and temperature in different locations. The analysis includes visualization of COVID-19 cases over time, temperature variations, and correlation between cases and temperature.

## Dataset
- **COVID-19 Data**: The COVID-19 data is sourced from a CSV file (`Age_County_Gender_19Cov.csv`) which contains information about cases by age, county, gender, and month.
- **Temperature Data**: The temperature data is obtained from multiple CSV files in the `temperature_dataset` folder. Each file contains monthly temperature records for different locations.

## Preprocessing
- COVID-19 and temperature datasets are loaded and preprocessed to ensure consistency and accuracy in analysis.
- Unnecessary columns are dropped, and data types are appropriately converted.

## Analysis
- **Visualization**: COVID-19 cases are visualized over time for specific locations. Monthly temperature variations are plotted for each year.
- **Correlation Analysis**: The correlation between COVID-19 cases and temperature is explored. Heatmaps are generated to visualize correlations between variables.

## Dependencies
- Python 3
- pandas
- numpy
- seaborn
- matplotlib

## Usage
1. Clone this repository to your local machine.
2. Ensure you have the required dependencies installed.
3. Run the Python script (`covid_temperature_analysis.py`) to perform the analysis.

## Contributors
- [Ofelia Lin] ([covid19](https://github.com/OfeliaLin/covid19/blob/main/The%20relation%20between%20temperature%20and%20Covid19%20.ipynb)
