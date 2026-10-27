# BlinkIT Grocery Sales Analysis

## Project Overview
This project analyzes BlinkIT grocery sales data using Python to explore product sales, outlet performance, customer ratings, and potential business improvement opportunities.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Excel

## Project Objectives
1. Understand business and sales performance.
2. Check missing values, duplicate records, outliers, and inconsistent category labels.
3. Analyze product and outlet performance and relationships between sales and other variables.
4. Identify improvement opportunities and develop practical business recommendations.

## Analysis Performed
### Objective 1: Business Understanding
- Product category distribution
- Outlet types, sizes, and locations
- Overall sales statistics
- Customer ratings and product performance

### Objective 2: Data Quality
- Missing-value analysis
- Duplicate-record checks
- Outlier detection using the IQR method
- Category standardization

### Objective 3: Sales Performance Drivers
- Sales by product category
- Sales by outlet type and location
- Correlation analysis of visibility, weight, ratings, and sales
- Comparison of high- and low-performing products and outlets

### Objective 4: Business Recommendations
- Highest-contributing products
- Best-performing outlets and location tiers
- Potential improvement opportunities
- Inventory, marketing, and operational recommendations

## Key Findings
- Highest-sales product category: FDU12
- Highest-sales outlet type: Supermarket Type1
- Highest-sales location tier: Tier 3
- Top 10 products' contribution: 1.8 %

## Recommendations
- Monitor availability of high-contributing products.
- Investigate categories with below-average sales and ratings.
- Review performance differences across outlets.
- Test targeted promotions before wider implementation.
- Consider location-specific inventory and marketing strategies.

## Project Files
- `BlinkIT_Sales_Analysis.ipynb` — Complete analysis notebook
- `BlinkIT Grocery Data.xlsx` — Original dataset, if redistribution is permitted
- `BlinkIT_Cleaned_Data.xlsx` — Standardized dataset
- `BlinkIT_Business_Recommendations.xlsx` — Recommendations and supporting tables

## How to Run
1. Download or clone the repository.
2. Install dependencies:
   `pip install pandas numpy matplotlib seaborn openpyxl notebook`
3. Start Jupyter Notebook:
   `python -m notebook`
4. Open `BlinkIT_Sales_Analysis.ipynb`.
5. Run all cells in order.

## Notes
Sales comparisons are based on the provided dataset. Correlations do not establish causation, and business recommendations require further validation.

## Project Status
Completed all 16 analytical tasks across four objectives.
