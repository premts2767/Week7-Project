# Week 7 Data Science Internship: Statistical Business Analysis

## Project Overview
This project performs a comprehensive statistical analysis of business data, focusing on customer churn and regional sales. All analyses are strictly based on the provided `customer_churn.csv` and `sales_data.csv` datasets.

## Objectives Achieved
- **Descriptive Statistics:** Computed key metrics (mean, median, mode, std dev, variance, min, max, quartiles, IQR) for relevant numerical features.
- **Distribution Analysis:** Created histograms, KDE plots, and box plots to visualize data distribution. Tested for normality using the Shapiro-Wilk Test.
- **Correlation Analysis:** Analyzed relationships among numerical variables using Pearson correlation and visualized them with a correlation heatmap.
- **Hypothesis Testing:**
  - Independent T-Test comparing Total Sales between East and West regions.
  - ANOVA test comparing Total Sales across all regions.
  - Independent T-Test comparing MonthlyCharges between churned and retained customers.
- **Confidence Intervals:** Calculated 95% confidence intervals and margins of error for significant financial metrics (Total Sales, Price, MonthlyCharges, TotalCharges).
- **Regression Analysis:** Modeled the linear relationship between Price and Total Sales, and MonthlyCharges and TotalCharges.

## Repository Contents
- `statistical_analysis.ipynb`: The main Jupyter Notebook containing the full analysis, code, and insights.
- `requirements.txt`: Required Python packages for this project.
- `hypothesis_tests_results.txt`: Text file summarizing the results of the hypothesis tests.
- `visualizations/`: Folder containing PNG images of the generated plots (histograms, box plots, heatmaps, regression plots).
- `statistical_report.pdf`: The final PDF report generated from the notebook.
- `customer_churn.csv` & `sales_data.csv`: Source datasets.

## How to Run
1. Ensure Python 3.10 is installed.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook to view or re-run the analysis:
   ```bash
   jupyter notebook statistical_analysis.ipynb
   ```
   
## Business Insights Summary
- The analysis confirmed strong relationships between charges and sales metrics.
- Churned customers exhibit significantly different monthly charges compared to those who are retained.
- Confidence intervals provide clear brackets for expected average sales and charges, which is vital for forecasting.
