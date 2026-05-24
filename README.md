# Northwind Traders: Global Supply Chain & Sales BI

**Author:** Alabi Faruk
**Role:** Data Analyst

## 📌 Project Summary
This project features an interactive, enterprise-grade Power BI dashboard designed to optimize global supply chain logistics, evaluate salesforce performance, and analyze the true impact of product discounts on profit margins for a global gourmet food supplier.

## 🏢 The Business Problem
Northwind Traders lacked centralized visibility into their operations. Executives relied on fragmented spreadsheets, making it difficult to optimize shipping routes across different countries, evaluate regional sales reps, or identify which product categories were secretly losing money due to heavy discounting. 

## 🛠️ Tools & Technologies Used
* **Power BI:** Data Modeling, DAX Engineering, Interactive Visualizations.
* **Data Sources:** 7 Relational CSV datasets (Customers, Products, Orders, Employees, Shippers).

## 🔬 Methodology
* **Data Modeling:** Established a unified Star Schema data model connecting isolated relational tables and built a dedicated Date Table for time-intelligence analysis.
* **DAX Engineering:** Authored custom DAX measures (e.g., `SUMX`) to accurately calculate Gross Revenue, Total Freight Costs, and Discount Impact dynamically across millions of rows.
* **Dashboard Architecture:** Designed a 3-page interactive executive dashboard segmented into Financial Overview, Product Intelligence, and Regional Operations, with synchronized cross-filtering.

## 💡 Key Insights & Business Impact
* **Revenue Optimization:** Uncovered that discontinued products were still generating **15% of total revenue ($184,990)**, prompting a recommendation to formally liquidate or reinstate these product lines.
* **Margin Protection:** Identified that the *Meat & Poultry* category was over-discounted (8.5% average), artificially inflating sales volume while sacrificing over $15,000 in gross margin.
* **Logistics Efficiency:** Revealed severe shipping inefficiencies; freight to Austria averaged $162 per order. Recommended routing more European freight through *Federal Shipping*, which provided the optimal balance of speed (7.4 days) and cost efficiency.
* **Salesforce Analytics:** Highlighted Margaret Peacock as the top-performing regional representative, generating over $232,000 in global sales.
