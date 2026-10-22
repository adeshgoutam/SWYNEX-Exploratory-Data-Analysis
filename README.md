# Exploratory Data Analysis (EDA) – Online Retail Dataset

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of an Online Retail dataset to understand sales performance, product demand, customer behaviour, and country-wise revenue distribution.

The objective is to transform raw transaction data into meaningful business insights using Python, Pandas, Matplotlib, and Seaborn.

## Objectives
- Understand the structure and quality of the dataset.
- Perform descriptive statistical analysis.
- Analyze revenue and monthly sales trends.
- Identify top-performing products and countries.
- Explore customer purchasing patterns.
- Detect unusual values and potential anomalies.
- Provide actionable business recommendations.

## Dataset Information
- **Dataset:** Online Retail
- **Rows:** 541,909
- **Original columns:** 8
- **Source:** UCI Machine Learning Repository – Online Retail dataset
- **Note:** The analysis uses `cleaned_online_retail.csv`. Missing values and unusual transactions are considered during interpretation.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn

## Analysis Performed
1. Data loading and overview
2. Missing-value and data-quality checks
3. Descriptive statistics
4. Revenue calculation using Quantity × UnitPrice
5. Monthly revenue trend analysis
6. Product performance analysis
7. Country-wise revenue analysis
8. Customer-level analysis
9. Outlier and anomaly investigation
10. Business insights and recommendations

## Key Findings
- **Total row-level revenue:** 9,747,747.93 in the dataset's currency units.
- **Unique customers:** 4,372.
- **Unique countries:** 38.
- **Unique invoices:** 25,900.
- **Top revenue country:** United Kingdom.
- **Top revenue product by recorded revenue:** DOTCOM POSTAGE.
- **Top revenue customer:** Customer ID 14646.
- **Highest revenue month:** November 2011.
- **Lowest revenue month:** December 2011.

## Business Recommendations
- Investigate product-level performance to identify items that contribute most to revenue.
- Use monthly sales trends to support inventory and sales planning.
- Segment customers by purchasing behaviour to improve retention strategies.
- Analyze postage separately from merchandise sales where appropriate.
- Investigate negative quantities, cancellations, and missing customer IDs before making final business decisions.
- Verify whether December 2011 represents a complete reporting period before comparing it with other months.

## Project Files
- `Exploratory_Data_Analysis.ipynb` – Notebook containing the analysis, code, and visualizations.
- `README.md` – Project overview, findings, and recommendations.
- `cleaned_online_retail.csv` – Dataset used for the analysis, if included or made available separately.

## How to Run
1. Download or obtain the dataset from its original source.
2. Open `Exploratory_Data_Analysis.ipynb` in Jupyter Notebook.
3. Update the dataset file path if necessary.
4. Run the notebook cells in order.

## Conclusion
This project demonstrates how Python-based EDA can help identify revenue patterns, product performance, customer behaviour, and potential data-quality issues. The findings can support further analysis and more informed business decisions.

**Disclaimer:** This is an educational portfolio project. Findings are descriptive and should be validated before being used for actual business decisions.
