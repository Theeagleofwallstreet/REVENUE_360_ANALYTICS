# REVENUE_360_ANALYTICS

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-teal.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)


This project analyzes monthly sales data to uncover revenue trends, customer behavior patterns, and opportunities for business growth. The analysis merges, cleans, and visualizes large datasets to support strategic decision-making across sales, marketing, and operations.


TO access the full article and the executive presentation, click the link below:

[**How Exploratory Data Analysis Helps Reduce Customer Churn: A Business-Driven METRO PLUS Case Study**](https://medium.com/@theeagleofwallstreet/how-exploratory-data-analysis-helps-reduce-customer-churn-a-business-driven-case-metro-plus-case-96bb2cd1ff4e)



##  **Project Structure**


├── SalesAnalysis.ipynb      # Full analysis notebook
├── data/
│   ├── Sales_January.csv
│   ├── Sales_February.csv
│   └── ...
└── output/
    ├── cleaned_data.csv
    ├── revenue_visuals.png
    └── city_sales.png

##  **Core Steps in the Workflow**

###  **Importing Libraries**

The notebook loads essential Python libraries for data manipulation and visualization.

###  **Data Collection & Merging**

All monthly CSV files are merged into one master dataset using `os` and `pandas`.

###  **Data Cleaning**

Includes:

* Handling missing values
* Fixing data type inconsistencies
* Removing invalid entries
* Parsing date/time information

###  **Feature Engineering**

* Adding `Month`, `City`, and `Hour` columns
* Deriving “Frequently Bought Together” product pairs

###  **Exploratory Data Analysis**

Visualizations explore:

* Monthly sales trends
* Best-selling products
* City-level performance
* Optimal advertising / sales hours

###  **Visualization**

Clean, simple charts styled in navy and teal following the project’s palette.


##  **Key Insights from the Analysis**

* High-value customers drive most revenue but are at risk due to inconsistent product experience.
* Certain regions are underserved and show strong growth potential.
* Product bundles reveal opportunities for targeted promotions.
* Peak sales hours indicate where marketing spend should be focused.


##  **How to Run the Project**

1. Clone the repository
2. Install required packages:

   ```bash
   pip install pandas matplotlib
   ```
3. Place monthly sales CSVs into the `/data/` folder
4. Run the notebook:

   ```bash
   jupyter notebook SalesAnalysis.ipynb
 
##  **Future Improvements**

* Build a predictive model for future sales
* Add dashboards (Streamlit/Power BI)
* Automate monthly merging and cleaning with a Python script


