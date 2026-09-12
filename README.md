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
