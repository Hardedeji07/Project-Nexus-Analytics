This project encompasses a sophisticated multi-dimensional analysis of financial systems, spanning individual credit risk, national fiscal positions, tax collection efficiency, and retirement payout trends. By leveraging diverse datasets—from corporate tax records to global personal finance benchmarks—the project identifies critical patterns in economic stability, institutional distribution, and fiscal management.
Key Analytical Pillars
●Credit & Risk Assessment: Analyzes a dataset of 10,000 individuals to understand the relationship between income, balance, and default status, providing a baseline for creditworthiness modeling.
●Fiscal Position & Manpower: Evaluates government expenditure trends, including manpower costs across various ministries and the broader fiscal position relative to GDP.
●Taxation Intelligence: Investigates corporate tax behaviors by residency and income group, alongside an efficiency analysis of tax collection costs per dollar collected.
●Retirement & Social Security: Tracks the evolution of retirement payouts under schemes like CPF LIFE and the Retirement Sum Scheme (RSS), highlighting shifts in social safety net utilization.
●Market Dynamics: Conducts volatility and return analysis for specific financial instruments (e.g., Bajaj Finance) to understand market price trends.
README.md
Financial and Fiscal Data Analytics Suite
This repository contains a comprehensive collection of Jupyter Notebooks dedicated to the analysis of financial, fiscal, and socio-economic datasets. The project aims to provide data-driven insights into economic health, institutional infrastructure, and individual financial behaviors.
Project Structure
Notebook	Focus Area	Key Metrics
Credit_Analysis_Dataset.ipynb	Individual Credit Risk	Income, Balance, Default Status
Fiscal Data Analysis...ipynb	Government Finance	Expenditure on Manpower, Revenue vs. GDP
Tax Collection Efficiency.ipynb	Operational Efficiency	Cost per dollar of tax collected
Retirement Payout Analysis.ipynb	Social Security	CPF LIFE and RSS payout trends
Taxable Companies Analysis.ipynb	Corporate Economics	Chargeable income and residency-based tax
GPFLB.ipynb	Global Finance	Debt-to-income, credit scores, savings ratios
Data Insights
●Tax Collection Efficiency: The mean cost per dollar of tax collected stands at approximately $0.86, showing a negative correlation (-0.62) with time, indicating improving efficiency over the years.
●Corporate Trends: There is a significant growth trend in both the number of taxable companies and total assessed income, with a strong correlation (0.98) between total income and net tax.
●Social Infrastructure: Analysis of "Baby Bonus" institutions reveals a high concentration of Childcare Centres (1,549) and Healthcare Institutions (1,505) within the supported ecosystem.
●Retirement: Base interest credited to CPF members has seen steady growth, with total interest exceeding $16.8B by 2020.
Requirements
To run these notebooks, the following Python packages are required:
●pandas
●numpy
●matplotlib
●seaborn
●yfinance (for market data)
●statsmodels
Usage
1.Ensure all source .csv and .xlsx files are in the working directory.
2.Open the desired notebook in a Jupyter environment.
Execute cells sequentially to generate descriptive statistics, correlation matrices, and visualizations
