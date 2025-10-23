# US Sales & Profitability Analysis 

This is a complete data analysis project performed in a Python Jupyter Notebook. The project involves cleaning, transforming, and analyzing a raw sales CSV file to uncover key insights into sales performance, profitability, and logistics.

All analysis, data cleaning, and visualizations are contained in the US_Sales_Analysis.ipynb notebook.

## Key Business Insights Discovered:

* Through exploratory data analysis in the notebook, I uncovered the following:

* Top Channel: The 'In-Store' channel is the largest driver of both sales and profit.

* Top Warehouse: WARE-NMK1003 is the top-performing warehouse by a significant margin.

* Discount Impact: Higher discounts (especially > 25-30%) are strongly correlated with negative profit, highlighting a need for stricter discount policies.

* Seasonal Trends: Sales and profit consistently peak in the final quarter (Oct-Dec) of each year.

* Logistics Bottlenecks: Analysis of logistics (Cell 14) showed that 'Processing Time' (Order to Ship) often takes longer than 'Shipping Time' (Ship to Delivery), identifying a key internal bottleneck.

* High-Value Targets: The notebook identifies the Top 10 Customers, Products, and Sales Teams, allowing the business to focus on high-performers.

## Tools & Libraries

* Python 3

* Jupyter Notebook: For all data cleaning, analysis, and visualization.

* Pandas: For data loading, cleaning, and manipulation.

* Matplotlib & Seaborn: For all static visualizations and plots.

## How to Run This Project

Ensure all files are in one folder:

* US_Sales_Analysis.ipynb

* US_Regional_Sales_Data.csv

Install the required libraries:

pip install pandas jupyterlab matplotlib seaborn


## Run Jupyter:

py -m jupyter lab


Open the US_Sales_Analysis.ipynb notebook and run the cells to see the complete analysis. The notebook is already saved with all plots and outputs visible.
