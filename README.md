# python-retail-sales-analysis
Python-based retail sales analysis using Pandas, exploratory data analysis, visualizations, and business insights.

# Online Retail Sales Analysis using Python

## Project Overview

This project analyzes online retail transaction data using Python to uncover sales trends, product performance, customer purchasing behavior, and country-wise revenue patterns.

The objective is to transform raw transaction data into meaningful business insights that can support data-driven decisions related to sales planning, product performance, customer retention, and business growth.

## Business Objectives

- Analyze monthly sales revenue and order volume.
- Identify top-performing products by revenue and quantity sold.
- Evaluate country-wise sales performance.
- Identify high-value customers and their revenue contribution.
- Understand weekday sales patterns.
- Calculate key business metrics, including Average Order Value (AOV).
- Examine cancellation patterns.
- Develop actionable business recommendations.

## Dataset

**Dataset:** Online Retail II

The dataset contains historical online retail transactions with information about invoices, products, quantities, transaction dates, prices, customers, and countries.

### Key Columns

| Column | Description |
|---|---|
| Invoice | Transaction invoice number |
| StockCode | Product identifier |
| Description | Product description |
| Quantity | Quantity purchased |
| InvoiceDate | Date and time of transaction |
| Price | Unit price |
| Customer ID | Customer identifier |
| Country | Customer's country |

## Tools and Technologies

- **Python** — Data analysis
- **Pandas** — Data cleaning, transformation, and analysis
- **NumPy** — Numerical operations
- **Plotly** — Interactive data visualizations
- **Jupyter Notebook** — Analysis environment

## Project Workflow

1. **Data Inspection:** Examined dataset structure, data types, missing values, and duplicates.
2. **Data Cleaning:** Prepared transaction records and handled data-quality issues.
3. **Feature Engineering:** Created transaction value and cancellation indicators.
4. **Exploratory Data Analysis:** Analyzed sales, products, customers, countries, and order patterns.
5. **KPI Analysis:** Calculated revenue, order volume, and Average Order Value.
6. **Data Visualization:** Created charts to communicate key findings.
7. **Business Insights:** Developed recommendations based on the analysis.

## Key Business Insights

- **Monthly Performance:** November 2010 recorded the highest monthly revenue in the analyzed period.
- **Country Performance:** The United Kingdom was the largest revenue-generating market.
- **Product Performance:** REGENCY CAKESTAND 3 TIER was the highest-revenue product among the analyzed products.
- **Popular Product:** WHITE HANGING HEART T-LIGHT HOLDER performed strongly in both revenue and quantity sold.
- **Customer Analysis:** The top 10 customers contributed approximately 14.13% of total revenue.
- **Weekday Analysis:** Thursday recorded the highest weekday revenue in the analyzed data.
- **Order Analysis:** Average Order Value was approximately 490.28 in the dataset's price units.
- **Cancellation Analysis:** Cancellation invoices were examined to identify potential areas for further investigation.

*Note: These findings are based on the current analysis and should be validated against the final cleaned dataset before publication.*

## Visualizations

The notebook includes visualizations covering:

- Monthly sales revenue trends
- Monthly order volume
- Top products by revenue
- Top products by quantity sold
- Country-wise revenue performance
- Top customers by revenue
- Sales revenue by weekday
- Average Order Value
- Cancellation invoice trends
- Product revenue versus quantity
- Order value distribution

## Business Recommendations

- Monitor sales trends to improve demand and inventory planning.
- Maintain adequate stock for high-performing products.
- Develop retention strategies for high-value customers.
- Investigate opportunities to expand sales in markets outside the United Kingdom.
- Review cancellation patterns to identify potential operational issues.
- Track revenue and order KPIs regularly to support business decisions.

## How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy plotly openpyxl jupyter
   ```

4. Place the dataset in the appropriate data folder, following the notebook's file path.
5. Open Jupyter Notebook and run the analysis notebook from top to bottom.

## Project Structure

```text
python-retail-sales-analysis/
├── data/
│   └── raw/
│       └── online_retail_II.xlsx
├── notebooks/
│   └── 01_Data_Audit.ipynb
└── README.md
```

*Adjust the folder structure above to match the actual files in your repository.*

## Conclusion

This project demonstrates the use of Python for practical retail sales analysis, from data preparation and exploratory analysis to visualization and business recommendations.

It highlights how transaction-level data can help businesses understand revenue trends, identify valuable products and customers, and discover opportunities for better sales planning.

## Author

**Ayushi Wankhede**

Aspiring Data Analyst | MCA (AI & ML)

Skills: Python, Pandas, SQL, Excel, Power BI

