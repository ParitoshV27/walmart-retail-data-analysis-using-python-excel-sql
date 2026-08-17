# Walmart Retail Sales Analysis
📌 **Project Overview**

- This project presents an end-to-end analysis of Walmart retail data using Python, SQL, Google BigQuery, Excel, and Power Query. The analysis explores sales performance, profitability, discounts, shipping costs, product categories, regional performance, and factors associated with loss-making transactions.
- The project combines data cleaning, exploratory data analysis, statistical hypothesis testing, SQL-based business analysis, and interactive dashboard development to extract meaningful business insights from the dataset.


🎯 **Objectives**

- Clean and prepare the dataset for analysis.
- Explore sales, profit, discount, and shipping-related patterns.
- Analyze product, customer, and regional performance.
- Investigate factors associated with loss-making transactions.
- Apply statistical tests to evaluate significant differences and relationships.
- Perform business analysis using SQL and advanced window functions.
- Build an interactive Excel dashboard to visualize key performance indicators and trends.


🛠️ **Tools & Technologies**

Tool	Usage

- Python - Data cleaning, EDA, visualization, and statistical analysis
- Pandas & NumPy - Data manipulation and preprocessing
- Matplotlib / Seaborn	- Data visualization
- SciPy / Statistical libraries	- Hypothesis testing and statistical analysis
- SQL	- Data querying and business analysis
- Google BigQuery	- SQL query execution
- Excel	- Dashboard development and visualization
- Power Query	- Data transformation and preparation
- GitHub	- Project documentation and version control



walmart-retail-sales-analysis/
│
├── README.md
│
├── data/
│   └── README.md
│
├── python/
│   └── walmart_retail_analysis.ipynb
│
├── sql/
│   └── walmart_retail_analysis.sql
│
├── excel/
│   └── walmart_retail_dashboard.xlsx
│
└── dashboard/
    └── dashboard_screenshot.png


- python/ — Data cleaning, exploratory data analysis, visualization, and statistical testing.
- sql/ — SQL queries covering aggregations, filtering, CTEs, subqueries, and window functions.
- excel/ — Excel workbook containing Power Query transformations, PivotTables, charts, KPIs, and the interactive dashboard.
- dashboard/ — Screenshot of the final Excel dashboard.
- data/ — Walmart Retail Dataset from Kaggle


🐍 **Python Analysis**

The Python component of this project focused on data preparation, exploratory data analysis, statistical testing, and profitability analysis.

**Key Areas**

- Data Cleaning & Preparation
  - Missing value treatment
  - Data type optimization
  - Feature engineering
    
- Exploratory Data Analysis
  - Distribution analysis
  - Product, regional, and customer performance
  - Correlation and relationship analysis
    
- Statistical Analysis
  - Chi-Square Test
  - Kruskal-Wallis Test
  - Dunn's Post-Hoc Test
  - One-Way ANOVA
    
- Profitability Analysis
  - Discount and profit relationships
  - Sales vs. profit analysis
  - Analysis of loss-making transactions
  - Shipping costs and profitability


🗄️ **SQL Analysis**

SQL analysis was performed using Google BigQuery to explore business performance and answer key questions related to sales, profit, products, customers, and regional performance.

Key Areas

- Data Exploration
  - Record counts and summary metrics
  - Sales and profit analysis
    
- Aggregation & Filtering
  - WHERE, GROUP BY, and HAVING
  - Sales and profit analysis across states, regions, categories, and sub-categories
  - Identification of loss-making groups
    
- Conditional Logic
  - CASE WHEN for categorizing and analyzing transactions
    
- Advanced SQL
  - Common Table Expressions (CTEs)
  - Subqueries
  - RANK() / DENSE_RANK()
  - PARTITION BY
  - Running totals
  - LAG() for month-over-month comparisons
  - Percentage contribution using window functions


📊 **Excel Dashboard**

An interactive dashboard was created in Microsoft Excel to present key business metrics and trends in a visual and accessible format.

Key Components

- Power Query
  - Data transformation and preparation
  - Data type corrections
  - Missing value handling
  - Feature creation
    
- Dashboard & Visualizations
  - KPI cards for key metrics
  - Sales and profit analysis
  - Product category and sub-category performance
  - Regional performance
  - Monthly sales trends
  - Interactive PivotCharts
 
- Interactivity
  - PivotTables
  - Slicers for filtering and exploring the data



🔍 **Key Findings**

- **Product categories showed statistically significant differences in profit distributions**, with post-hoc analysis identifying significant differences between the category groups.
  
- **Customer segments did not show a statistically significant difference in average profit**, based on the ANOVA results.

- **Ship modes did not show a statistically significant difference in delivery duration**.
  
- **Discounting showed a trade-off between sales and profitability**: moderate discounts could support sales, while higher discounts were associated with reduced profit margins.

- **Loss-making transactions tended to have lower sales values and relatively higher shipping costs**, suggesting that shipping costs can have a significant impact on profitability.
  
- **One state recorded an overall negative profit**, despite generating positive sales.
  
- SQL analysis was used to further examine sales and profit performance across **regions, states, product categories, and sub-categories**, along with rankings, running totals, month-over-month comparisons, and percentage contributions.


📁 **Dataset**

The dataset contains retail transaction data covering information such as:

- Sales and profit
- Product categories and sub-categories
- Customer segments
- Geographic information
- Order and shipping details
- Discounts and shipping costs

The raw dataset is not included in this repository. Please refer to the dataset source and applicable usage terms before using or redistributing the data.


🚀 **How to Explore the Project**

- Python Analysis — Open the Colab notebook in the python/ directory to explore the data cleaning, EDA, visualizations, and statistical analysis.
  
- SQL Analysis — View the SQL file in the sql/ directory for business queries, aggregations, CTEs, subqueries, and window functions.
  
- Excel Dashboard — Open the workbook in the excel/ directory to explore the interactive dashboard, PivotTables, charts, KPIs, and slicers.


