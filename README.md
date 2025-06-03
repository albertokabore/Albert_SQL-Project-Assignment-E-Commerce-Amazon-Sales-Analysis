# Albert_SQL-Project-Assignment-E-Commerce-Amazon-Sales-Analysis

SQL Project Assignment: E-Commerce Amazon Sales Analysis 

Dataset Details 

This project uses an e-commerce dataset from Kaggle. The dataset includes transactional data from Amazon, 
providing detailed insights into sales trends, product performance, and fulfillment processes. 

Dataset Schema 

• Category: Type of product (e.g., Electronics, Clothing). (String) 

• Size: Size of the product (e.g., S, M, L). (String) 

• Date: Date of the sale. (Date) 

• Status: Status of the sale (e.g., Completed, Canceled). (String) 

• Fulfillment: Method of fulfillment (e.g., Amazon Fulfilled, Seller Fulfilled). (String) 

• Style: Style of the product (e.g., Casual, Formal). (String) 

• SKU: Stock Keeping Unit, a unique identifier for products. (String) 

• ASIN: Amazon Standard Identification Number, another unique product identifier. (String) 

• Courier Status: Status of the courier (e.g., Delivered, In Transit, Lost). (String) 

• Qty: Quantity of the product sold in a transaction. (Integer) 

• Amount: Amount of the sale in a specific currency. (Float)

• B2B: Indicates if the sale was business-to-business. 
(Boolean) 

• Currency: Currency used for the sale (e.g., USD, EUR). (String) 

Detailed Problem Statement 

You are a Data Analyst for a mid-sized e-commerce company that sells products on Amazon. The company is looking 
to optimize its sales strategies by leveraging its Amazon sales data. Your task is to clean, analyze, and derive 
actionable insights from the dataset to assist the business team in making data-driven decisions. 

The project is divided into multiple phases, simulating real-world data analysis workflows: 

Phase 1: Data Exploration and Quality Check 

1. Understand the Dataset: 

o Review the dataset structure, types of data, and relationships between columns. 

o Identify primary and foreign keys (if applicable).

o Document the schema in detail. 

2. Identify Data Issues: 

o Missing or null values in fields like Amount, Courier Status, or Size. 

o Duplicate records or invalid entries in identifiers like SKU and ASIN. 

o Check for inconsistent or incorrect values in categorical fields like Category, Status, and Currency.

Deliverable: A detailed report of findings, listing all issues and assumptions about the dataset. 

Phase 2: Data Cleaning and Transformation

To ensure accurate analysis, clean and preprocess the data: 

• Handle Missing Data: Impute values where possible or remove incomplete rows if they cannot be reliably 
filled. 

• Normalize Currency: Convert all Amount values to USD using a given currency conversion table. 

• Remove Duplicates: Identify and delete duplicate rows using unique identifiers like SKU or ASIN. 

• Data Standardization: Ensure consistent formatting for columns such as Date, Category, and Status. 

• Derived Columns: 

o Calculate profit margins using a static cost multiplier (e.g., 70% of Amount as cost). 

o Create a Month column from the Date field to analyze trends. 

Deliverable: SQL scripts and a cleaned dataset ready for analysis. 

Phase 3: Business Questions and Insights 

Using SQL, answer the following business-critical questions:

1. Category Performance: 

o Which product categories generate the highest revenue and quantity sold? 

o Are there any low-performing categories that need attention? 

2. Seasonal Sales Trends: 

o What are the monthly and weekly sales trends? 

o Identify peak sales periods. 

3. Fulfillment Efficiency: 

o How do sales and revenue differ across fulfillment methods (Amazon Fulfilled vs. Seller Fulfilled)? 

o Does one method correlate with fewer canceled or lost courier statuses? 

4. Product Size Analysis:

o Which sizes are most popular in terms of quantity sold? 

o Are there specific sizes that are consistently low in stock but high in demand? 

5. Courier Impact on Revenue: 
o How does Courier Status (e.g., Delivered, Lost) impact revenue? 

o What is the percentage of lost or delayed shipments? 

6. B2B vs. B2C Sales: 

o Compare revenue and quantity sold for B2B vs. B2C transactions. 

o Are there any specific categories or styles that perform better in B2B sales? 

Deliverable:

SQL queries answering these questions, along with tabular results and insights summarized in a report. 

Phase 4: Advanced Reporting and Visualization 

Generate detailed reports to present insights clearly: 

• Sales Leaderboard: 

o Top 5 products by revenue. 

o Top 5 products by quantity sold. 

• Category Trends: 

o Create a pivot table to show monthly revenue for each category. 

o Rank categories based on revenue and sales quantity.

• Performance by Fulfillment:

o Use window functions to compare revenue by fulfillment method and rank fulfillment methods. 

• Visualization (Optional): 

If possible, use Power BI or Tableau to build an interactive dashboard highlighting: 

o Monthly sales trends. 

o Category performance.

o Courier status impact. 

Deliverable: SQL scripts and a report or dashboard 
summarizing the findings.

Phase 5: Recommendations and Business Strategy 

Using the insights derived, propose actionable strategies to optimize operations: 

• Identify underperforming categories or sizes. 

• Recommend stock adjustments for popular but low-stock products. 

• Highlight fulfillment methods needing improvement. 

• Suggest strategies to reduce lost shipments. 

• Present potential growth areas in B2B sales. 

Deliverable: A well-structured business memo detailing data-driven recommendation. 

Expected Outputs 

1. Cleaned dataset. 

2. SQL scripts for analysis and transformation. 

3. Insights report summarizing key findings and answers to business questions. 

4. Optional: An interactive dashboard for visualization. 

5. Business memo with actionable recommendations. 

Grading Criteria 

• Technical Accuracy (40%): Correctness of SQL queries and outputs. 

• Data Cleaning (20%): Thorough handling of data quality issues. 

• Business Insights (20%): Relevance and depth of insights. 

• Presentation (10%): Clarity and organization of results and recommendations. 

• Bonus (10%): Effective use of visualizations or advanced SQL features. 

SQL by Manisha 