# AWS End-to-End Data Pipeline & Sales Dashboard

## 📌 Project Overview
Built an end-to-end data pipeline using AWS services and developed a Power BI dashboard to analyze e-commerce sales data.

## ⚙️ Tech Stack
- AWS S3
- AWS EC2
- AWS Athena
- Python (Pandas)
- SQL
- Power BI

## 🔄 Pipeline Flow
1. Uploaded raw CSV data to S3
2. Pulled data into EC2 and cleaned using Python (Pandas)
3. Stored processed data back to S3
4. Queried data using AWS Athena (SQL)
5. Built interactive dashboard in Power BI

## 📊 Dashboard Insights
- Furniture category generates highest revenue
- Electronics shows high sales but moderate profitability
- Some categories contribute to losses
- Sales vary significantly across states
- Monthly trends reveal fluctuations in demand

## 📷 Dashboard Preview
![Dashboard](dashboard/dashboard.png)

## 📂 Project Structure
- dashboard/ → Power BI dashboard screenshot
- screenshots/ → Athena query results
- data/ → cleaned dataset
- queries.sql → SQL queries used

## 🚀 Key Skills Demonstrated
- Data Engineering (ETL pipeline)
- Data Cleaning (Python Pandas)
- SQL Analytics (Athena)
- Data Visualization (Power BI)
