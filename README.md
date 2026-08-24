# Ecommerce-Logistics-Analysis
An analysis of the impact of shipping costs on sales profitability in the Brazilian e-commerce sector. The goal was to identify product categories where logistics consume an excessively large share of revenue.

Technologies Used

- Database: PostgreSQL (Relational modeling, ETL data import)

- Query Language: SQL (Joins, Aggregations, Case Statements, NULLIF)

- Visualization: Power BI (Native SQL Queries, DAX, Interactive Dashboards)

Folder Contents

- Database_Setup.sql – Code creating table structures and defining relationships (Primary/Foreign Keys).

- margin_analysis.sql – Main analytical engine joining order, product, and price data.

- Olist_Delivery_Analysis.pbix – Interactive Power BI report.

Key Findings

- Identified categories (e.g., flores, moveis_casa) where shipping costs exceed 25% of the product value.

- Created an Estimated Profit metric to quickly filter categories operating on negative margins after accounting for logistics.

- Built a dashboard enabling dynamic segmentation into "Cheap" and "Expensive" shipping categories to support strategic decisions around free shipping policies.
