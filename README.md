# Credit Card Financial Analysis – Weekly Dashboard

## 📌 Project Overview
This project focuses on analyzing weekly credit card financial performance using transaction-level and customer-level data. The goal is to identify key revenue drivers, understand customer behavior, and monitor financial trends through interactive Power BI dashboards.

The project simulates a real-world business intelligence workflow by integrating data from a database and validating dashboard refresh behavior.

---

## 🛠️ Tools & Technologies Used
- **Power BI** – Data visualization and dashboard creation  
- **MySQL** – Data storage and management  
- **DAX** – Measures and calculated fields  
- **CSV Files** – Initial data source  

---

## 🔄 Data Pipeline
1. Raw data was available in CSV format.
2. CSV data was loaded into a MySQL database.
3. Power BI was connected to MySQL for data import.
4. DAX queries were used for data processing and modelling to create columns like age-group, income-group and week-num.
5. Interactive dashboards were developed for weekly reporting.

To validate the data pipeline, new records were inserted into the MySQL database and the Power BI dashboards were refreshed to confirm that updated data was reflected correctly.

---

## 📊 Dashboards Included

### 1️⃣ Credit Card Transaction Report
This dashboard focuses on revenue analysis based on financial and transactional factors, including:
- Revenue by card category
- Revenue by transaction type based on used chip
- Weekly and Quartelry revenue trends
- Revenue by Expenditure Categoy
- Total transaction volume 

📄 Report available in PDF format under the **Reports** folder.

---

### 2️⃣ Credit Card Customer Report
This dashboard analyzes revenue from a customer perspective, focusing on:
- Revenue by customer demographics with gender legend
- Revenue by Income groups
- Revenue by Education
- Revenue by Job Role
- Revenue by Age Group
- Revenue by Marriage Status
- Revenue by Dependend Count
- Top 5 States based on Revenue
- Weekly Revenue Trends
- Identification of high-value customers

📄 Report available in PDF format under the **Reports** folder.

---

## 📈 Key KPIs
- Total Revenue  
- Total Transactions  
- Interest Earned  
- Total Transaction Count  
- Average Customer Satisfaction Score
- Total Customer Income

---

## 📌 Detailed Insights
Detailed business insights derived from the dashboards are documented in the **Notes** folder:
- [Business Insights](Notes/Business-Insights.md)


---

## 🖼️ Dashboard Preview
Screenshots of both dashboards are available in the **Screenshots** folder for quick reference.

---

## ✅ Conclusion
This project demonstrates an end-to-end business intelligence workflow, including database integration, data modeling, dashboard development, and refresh validation. It reflects a practical approach to financial data analysis and reporting using industry-relevant tools.

