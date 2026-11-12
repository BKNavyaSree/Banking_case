# Banking_case
My Data Analytics project
Banking Analysis & Power BI Dashboard
Project Overview
The Banking Analysis Dashboard is a data analytics project developed
using Microsoft Power BI and Python to analyze banking customers,
loans, deposits, account balances, and customer engagement.

The project uses data analysis and interactive visualizations to help
understand customer financial profiles and support data-driven
decision-making in the banking and financial services sector.
Problem Statement
Banks need to understand customer financial profiles and lending
patterns to make informed decisions and reduce the risk of financial
losses. Analyzing customer information, loans, deposits, and account
activities can help identify useful trends and support better banking
strategies.
Project Objectives
- Analyze customer banking and financial information.
- Understand loan, deposit, and credit card balance patterns.
- Examine customer demographics, income groups, and engagement.
- Create meaningful KPIs for banking operations.
- Build interactive Power BI dashboards for business insights.
- Perform exploratory data analysis (EDA) using Python.
Tools and Technologies
  Tool / Technology       Purpose
  Microsoft Power BI      Dashboard development and data visualization
Python                  Exploratory data analysis
Pandas                  Data loading and manipulation
NumPy                   Numerical operations
Matplotlib              Data visualization
Seaborn                 Statistical visualization
Jupyter Notebook        Python analysis environment
Microsoft Excel / CSV   Dataset storage and preparation
Project Structure
Banking-Analysis/
│
├── Banking/
│   ├── Banking Dashboard.pbix
│   ├── Banking Dashboard (2025).pbix
│   ├── Banking.xlsx
│   ├── Banking.csv
│   ├── Banking.pptx
│   ├── Banking Report.docx
│   ├── clients.csv
│   │
│   ├── datasets/
│   │   ├── banking-clients.csv
│   │   ├── banking-realtionships.csv
│   │   ├── gender.csv
│   │   └── investment-advisiors.csv
│   │
│   └── BG/
│       ├── Old Design/
│       ├── New Design/
│       └── Demo Design/
│
├── BankEDA (Version 1).ipynb
└── BankEDA (Version 2).ipynb
Note: The folder and file names above reflect the uploaded project
archive.
Dashboard Features
The Power BI report includes the following dashboard views:
1. Home Dashboard
- Overview of important banking KPIs.
- Customer and financial summary.
- Interactive navigation to other report pages.
2. Loan Analysis
- Bank loan analysis.
- Business lending analysis.
- Credit card balance analysis.
- Loan patterns across customer categories.
3. Deposit Analysis
- Bank deposits.
- Savings account balances.
- Checking account balances.
- Foreign currency account balances.
4. Summary Dashboard
- Consolidated banking metrics.
- Customer and account insights.
- Comparison of important financial indicators.
Key Performance Indicators (KPIs)
The project uses measures such as:
- Total Clients: Distinct count of banking customers.
- Total Loan: Combined bank loans, business lending, and credit
  card balance.
- Bank Loan: Total amount of bank loans.
- Business Lending: Total business lending amount.
- Total Deposit: Combined bank deposits, savings, checking, and
  foreign currency accounts.
- Total Fees: Estimated processing fees based on the loan amount
  and fee structure.
- Credit Card Balance: Total outstanding credit card balance.
- Engagement Length: Customer engagement duration.
Data Preparation and Transformation
The project includes data preparation steps such as:
- Creating an engagement timeframe based on customer joining dates.
- Calculating customer engagement days.
- Categorizing estimated income into income bands.
- Creating processing fee values based on fee structure.
- Connecting related banking tables using common keys and
  relationships.
Exploratory Data Analysis (Python)
The Jupyter notebooks perform exploratory data analysis using Pandas,
NumPy, Matplotlib, and Seaborn.

Analysis includes:
- Dataset shape and structure.
- Univariate analysis of categorical and numerical variables.
- Bivariate analysis of customer attributes.
- Distribution analysis of income and account balances.
- Correlation analysis using heatmaps.
- Relationship analysis between deposits, savings, loans, and other
  financial variables.
How to Run the Project
A. Open the Power BI Dashboard
1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open Banking Dashboard.pbix or Banking Dashboard (2025).pbix.
4. If Power BI asks for the data source location, update the source
   path to the CSV or Excel dataset included in the repository.
5. Refresh the data if required.
6. Explore the dashboard pages and interactive filters.
B. Run the Python EDA Notebooks
1. Install Python and Jupyter Notebook, or use Google Colab.
2. Open either BankEDA (Version 1).ipynb or
   BankEDA (Version 2).ipynb.
3. Upload the required Banking.csv dataset to the notebook
   environment.
4. If necessary, update the CSV file path in the notebook.
5. Install the required libraries:
pip install pandas numpy matplotlib seaborn jupyter
6. Run the notebook cells sequentially to reproduce the analysis and
   visualizations.
Key Insights
The exploratory analysis highlights patterns such as:
- Customers with higher bank deposits may also maintain higher savings
  and checking account balances.
- Age and estimated income can be associated with differences in
  savings and account balances.
- Business lending and bank loans can show relationships in customer
  financial profiles.
- Customer nationality, occupation, income band, and other demographic
  attributes can be explored to understand banking patterns.
These are exploratory observations from the available dataset and should
not be interpreted as proof of causation or as a validated loan-default
prediction model.
Project Outcome
The project demonstrates how banking data can be transformed into
meaningful insights through Python-based exploratory analysis and
interactive Power BI dashboards. It provides a consolidated view of
customer profiles, deposits, loans, account balances, and engagement
metrics to support banking analysis and business decision-making.
Future Enhancements
- Add loan repayment and loan-default analysis using a verified
  outcome dataset.
- Develop and validate a machine learning model for credit risk
  prediction.
- Include more advanced customer segmentation.
- Add time-based analysis of customer transactions and financial
  trends.
- Improve dashboard interactivity and automated data refresh.
