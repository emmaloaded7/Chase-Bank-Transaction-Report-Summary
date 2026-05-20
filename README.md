# Chase-Bank-Transaction-Report-Summary Using PowerBI
## Project Objective
The objective of this project was to analyze customer banking transactions and account activities across different states, transaction channels, card types, and age groups using Power BI.

## Dataset Used
[Chase-Bank-Transaction-Report-Summary](https://github.com/emmaloaded7/Chase-Bank-Transaction-Report-Summary/blob/main/chase_bank_transaction_dataset.xlsx)

## Question KPI
1. Financial KPIs
* What is the total account balance?
* What is the total transaction amount?
* How much transaction fee was generated?
2. Customer Behavior KPIs
* Which age group performs the highest transactions?
* Which card type is used the most?
* Which banking channel is most preferred?
3. Geographic KPIs
* Which states contribute the highest transaction volume?
* Which regions have lower transaction activity?
4. Operational KPIs
* What percentage of transactions were completed vs failed?
* Which transaction type occurs most frequently?

[Chase-Bank-Transaction-Report-Summary](https://github.com/emmaloaded7/Chase-Bank-Transaction-Report-Summary/blob/main/dashboard.png)

##Process

Step 1 — Data Collection
- Imported banking transaction dataset into Power BI
Dataset included:
* Customer information
* Transaction details
* States
* Card types
* Channels
* Transaction fees
* Account balances

Step 2 —  Data Cleaning
* Performed data cleaning using Power Query:
* Removed duplicates
* Fixed inconsistent text formatting
* Corrected data types
* Standardized categorical values

Step 3 — Data Transformation
- Created calculated measures using DAX
- Generated KPIs:
* Total Balance
* Total Transactions
* Total Transaction Fees
- Grouped customers into age categories
  
Step 4 — Dashboard Design
- Created interactive visuals including:
* KPI Cards
* Donut Charts
* Line Chart
* Map Visualization
* Transaction Table
* State Slicers
Applied a consistent banking-style blue theme for better presentation.

## Dashboard
<img width="1366" height="768" alt="dashboard" src="https://github.com/user-attachments/assets/2a48a971-1826-4585-bd71-d57357c023f5" />

## Project Insights
1. Financial Insights
* Total account balance reached approximately $75.44M
* Total transaction value exceeded $11.41M
* Transaction fees generated about $88.26K
2. Customer Insights
* Customers aged 35–44 contributed one of the highest transaction volumes
* Credit card transactions slightly exceeded debit card usage
* Mobile app and online banking channels were among the most used transaction methods
3. Geographic Insights
* Some states recorded significantly higher transaction activity than others
* Transaction distribution across the United States showed strong regional engagement
4. Operational Insights
* Most transactions were successfully completed
* ATM withdrawals, bill payments, and card payments were among the most frequent transaction types
* Failed transactions represented a smaller portion of total activities
## Final Conclusion

The Chase Bank Transaction Dashboard successfully provided a comprehensive overview of banking activities and customer transaction behavior.
