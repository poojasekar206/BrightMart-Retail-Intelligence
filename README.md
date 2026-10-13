# BrightMart Retail Intelligence and Sales Forecasting Solution

## Project Overview
BrightMart is a retail business that needs to turn sales data into actionable business insights. This project uses Python, data analysis, visualisation, and machine learning to examine retail performance and estimate next-month product demand.

## Business Objectives
- Analyse revenue, costs, profit, and profit margin.
- Compare regional and product performance.
- Explore the relationship between advertising spend and revenue.
- Build a regression model to predict next-month unit demand.
- Provide practical recommendations for management.

## Dataset
**File:** `retail_sales.csv`

The dataset contains 98 records and 12 original columns covering retail sales information, including dates, products, regions, units sold, prices, costs, advertising spend, discounts, stock availability, customer ratings, and next-month demand.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- GitHub

## Analysis Approach
1. Load and inspect the dataset.
2. Identify duplicate records and missing values.
3. Clean the data and document assumptions.
4. Calculate revenue, cost, profit, and profit margin.
5. Analyse monthly, regional, and product performance.
6. Visualise advertising spend against revenue.
7. Train and evaluate a Linear Regression model.

## Key Findings
- Advertising spend and revenue have a Pearson correlation of 0.908 in the analysed dataset. This indicates a strong positive linear association, not proof of causation.
- Regional and product comparisons are included in the notebook to identify differences in revenue and profitability.
- The model's chronological test produced an MAE of 0.95 units, an RMSE of 1.16 units, and an R² of 0.973.

## Model Evaluation
The regression model predicts `Next_Month_Units_Demand`.

| Metric | Result |
|---|---:|
| MAE | 0.95 units |
| RMSE | 1.16 units |
| R² | 0.973 |

These are preliminary results from a small test period. The target definition, feature availability, and potential data leakage must be checked before treating the model as a reliable forecasting tool.

## Limitations
- The dataset contains only 98 records spanning 12 months.
- The chronological test covers only the final three months.
- Advertising correlation does not establish causation.
- Profit calculations depend on the assumptions documented in the notebook.
- The model requires further validation before operational use.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required packages:

   `pip install pandas numpy matplotlib seaborn scikit-learn openpyxl`

3. Download or clone this repository.
4. Keep `retail_sales.csv` in the same directory as the notebook.
5. Open `BrightMart_Retail_Analysis.ipynb` in Jupyter Notebook.
6. Run the cells from top to bottom.

## Future Improvements
- Validate the target construction and prevent data leakage.
- Evaluate performance across multiple rolling time-based test periods.
- Compare Linear Regression with other suitable models.
- Incorporate more historical sales data.
- Develop an interactive dashboard.
- Investigate advertising effectiveness using additional explanatory variables.

## Author
Pooja G

This project was developed as a Python data analytics and machine-learning capstone.
