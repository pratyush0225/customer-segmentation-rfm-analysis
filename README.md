# customer-segmentation-rfm-analysis
Customer segmentation using RFM analysis on the Online Retail II dataset
Customer Segmentation Using RFM Analysis

Project Overview

This project analyzes the Online Retail II dataset to segment customers based on their purchasing behavior using Recency, Frequency, and Monetary (RFM) analysis.

The goal is to identify valuable customers, understand purchasing patterns, and derive actionable insights for customer retention and marketing strategies.

Dataset

* Source: Online Retail II — UCI dataset hosted on Kaggle
* Original records: 1,067,371
* Original columns: 8
* Key variables: Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, Country

Methodology

1. Explored the dataset and identified missing values, duplicate records, cancelled invoices, and invalid quantities and prices.
2. Cleaned the data using explicit filtering rules.
3. Calculated transaction revenue as Quantity × Price.
4. Aggregated transaction data at the customer level.
5. Calculated RFM metrics:
    * Recency: Time since the customer’s most recent purchase.
    * Frequency: Number of purchases, based on the project’s invoice-counting method.
    * Monetary: Total customer spending.
6. Scored customers and assigned them to behavioral segments.
7. Visualized customer distribution and revenue by segment.

Customer Segmentation Results

Segment	Customers
Lost / Hibernating	2,144
Champions	1,289
Loyal Customers	985
Potential Loyalists	733
At Risk	560
Recent Customers	167
Total	5,878

Key Insights

* Champions form a high-value segment and generated the highest total revenue in the analysis.
* Loyal Customers represent an important group for retention and repeat-purchase campaigns.
* Lost / Hibernating customers form the largest segment by customer count, suggesting an opportunity to investigate reactivation campaigns.
* At Risk customers may benefit from targeted retention efforts.
* Potential Loyalists could be nurtured toward more frequent purchasing.

Business Recommendations

* Reward Champions with loyalty benefits and personalized offers.
* Encourage Potential Loyalists to make repeat purchases.
* Test reactivation campaigns for Lost / Hibernating customers.
* Prioritize At Risk customers for retention outreach.
* Measure campaign conversion, incremental revenue, and retention before concluding that a campaign is effective.

Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* RFM Analysis

Repository Contents

* notebook07fe95734b.ipynb — Data cleaning, exploratory analysis, RFM scoring, customer segmentation, and visualizations.

Limitations

RFM segments describe historical purchasing behavior; they do not, by themselves, establish why customers stopped purchasing or prove the effectiveness of marketing campaigns. Results depend on the cleaning rules, observation period, and segmentation thresholds.

Conclusion

This project demonstrates how transactional data can be transformed into customer-level metrics and actionable customer segments to support data-driven marketing and retention decisions.
