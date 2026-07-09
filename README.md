# snowflake_bookings_analytics


This project demonstrates an end-to-end data engineering workflow built on Snowflake, following the Medallion Architecture (Bronze, Silver, Gold) to transform raw hotel booking data into business-ready datasets for analytics and reporting.

The pipeline begins by ingesting raw CSV files into a Bronze layer, where data is stored without modification. A Silver layer performs data cleansing, validation, and standardization, including handling invalid dates, correcting booking status values, validating email formats, normalizing text fields, and converting data types. Finally, a Gold layer creates analytical tables optimized for reporting, including daily booking summaries, city-level revenue aggregations, and a clean booking fact table.

The curated Gold layer is connected to Power BI, where interactive dashboards provide insights into revenue trends, booking performance, room type analysis, city-level revenue, and operational KPIs.

Project Highlights
Designed a scalable Bronze → Silver → Gold data pipeline in Snowflake.
Built reusable SQL transformations for data cleaning and validation.
Implemented business-ready aggregation tables for reporting.
Optimized data for analytical workloads using the Medallion Architecture.
Connected Snowflake directly to Power BI for real-time business intelligence.
Developed interactive dashboards featuring KPIs, revenue analysis, booking trends, and operational insights.


Technologies Used
Snowflake
SQL
Power BI
CSV Data Ingestion
Medallion Architecture (Bronze, Silver, Gold)
Data Cleaning & Transformation
Business Intelligence & Data Visualization


<img width="1844" height="1068" alt="image" src="https://github.com/user-attachments/assets/49ef2d5c-efcf-4bca-a533-8a27e177245e" />





<img width="2002" height="1064" alt="image" src="https://github.com/user-attachments/assets/86e1f388-ea66-4275-9f25-deb8a8300ad0" />




