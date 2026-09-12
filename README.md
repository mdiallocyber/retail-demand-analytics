# retail-demand-analytics
End-to-end retail analytics project using Python, SQL, Tableau, and machine learning to analyze product performance and predict demand
## Project Overview
This project explores retail sales and inventory data to understand product performance, store trends, and demand patterns.

The workflow includes:

- Data cleaning and preprocessing
- Exploratory data analysis
- SQL-based analysis
- Feature engineering
- Machine learning model development
- Model evaluation and comparison

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SQL
- SQLite
- Jupyter Notebook
- GitHub

## Dataset

The dataset contains retail store information related to sales, inventory, products, and other factors that can influence demand.

File included:

`retail_store_inventory-selected-columns.csv`

The cleaned data was also stored in a SQLite database:

`retail_sales.db`

## Analysis

The project investigates questions such as:

- Which products and categories generate the strongest performance?
- How does demand vary across different retail conditions?
- What variables appear to have the strongest relationship with demand?
- Can historical retail data be used to predict future demand?

## Machine Learning

Several regression approaches were tested to predict retail demand.

Initial models produced:

- Linear Regression R²: approximately **0.35**
- Random Forest R²: approximately **0.29**

After improving the features and modeling approach, the final regression model achieved:

- **MAE:** 7.42
- **RMSE:** 8.60
- **R²:** 0.994

The large improvement demonstrates the importance of feature selection and identifying variables that strongly explain the target.

## Repository Structure

```text
retail-demand-analytics/
│
├── README.md
├── retail_analysis.ipynb
├── retail_sales.db
└── retail_store_inventory-selected-columns.csv
```
## Tableau Dashboard

An interactive Tableau dashboard was created to visualize key patterns in the retail dataset.

The dashboard includes:

- **Sales by Category** – compares total units sold across product categories
- **Sales by Region** – compares sales performance across geographic regions
- **Monthly Sales Trend** – shows changes in units sold over time
- **Inventory by Category** – compares inventory levels across product categories

The dashboard also includes interactive filtering, allowing users to select a product category and dynamically update the other visualizations.

### View Interactive Dashboard

[View the Retail Sales & Inventory Dashboard on Tableau Public](https://public.tableau.com/app/profile/mohamed.diallo3513/viz/RetailSalesInventoryDashboard_17891815893930/Dashboard1?publish=yes)

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Scikit-learn
- Matplotlib
- Tableau
- Git & GitHub

## Key Takeaways

This project demonstrates an end-to-end data analytics workflow, including data cleaning, exploratory analysis, predictive modeling, data visualization, and communicating results through an interactive dashboard.
