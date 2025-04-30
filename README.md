# Years of Experience and Salary Data Analysis

## Project Overview
This project analyzes the relationship between years of professional experience and salary using Python data analysis tools. The analysis explores patterns in compensation based on experience levels and provides statistical insights and visualizations to understand this relationship better.

## Dataset
The dataset (`Salary_Data.csv`) contains information about:
- Years of professional experience
- Corresponding salary amounts in USD

## Requirements
To run this analysis, you'll need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

You can install these dependencies using pip:
```
pip install pandas numpy matplotlib seaborn
```

## Project Structure
- `Experience_Salary_Analysis.ipynb`: Jupyter notebook containing all code and analysis
- `Salary_Data.csv`: Dataset file (place in the same directory as the notebook)
- `salary_analysis_visualizations.png`: Output visualization with four plots
- `salary_boxplot.png`: Additional output visualization showing salary distribution

## Features
This analysis includes:

### 1. Data Loading and Exploration
- Loading the dataset from CSV
- Error handling for file not found cases
- Basic data exploration (head, info, checking for missing values)

### 2. Data Analysis
- Descriptive statistics computation
- Experience level categorization (Entry, Mid, Senior, Expert)
- Group-based statistical analysis
- Correlation analysis between experience and salary
- Calculation of average salary increase per year of experience

### 3. Data Visualization
- Line chart showing salary trends across years of experience
- Bar chart showing average salary by experience level
- Histogram showing the distribution of salaries
- Scatter plot with regression line showing the relationship between experience and salary
- Box plot showing salary distribution across different experience levels

## Key Findings
The analysis reveals:
1. Strong positive correlation between years of experience and salary
2. Clear salary differentiation between experience levels
3. Specific average salary increase per year of experience
4. Salary distribution patterns across the workforce
5. Quantitative comparison between entry-level and expert-level compensation

## How to Run
1. Ensure all required libraries are installed
2. Place the `Salary_Data.csv` file in the same directory as the notebook
3. Run the Jupyter notebook `Experience_Salary_Analysis.ipynb`
4. Visualizations will be saved to the local directory and displayed in the notebook

## Notes
- The code includes handling for missing data, although none exists in this dataset
- Experience level categorization can be adjusted by modifying the bin ranges
- The visualization parameters (colors, styles, etc.) can be customized in the code

## Future Improvements
Potential enhancements to this analysis could include:
1. Including additional factors that may affect salary (education, industry, location)
2. Implementing predictive modeling to forecast salary based on experience
3. Adding interactive visualizations for more dynamic exploration
4. Performing outlier analysis and impact assessment
