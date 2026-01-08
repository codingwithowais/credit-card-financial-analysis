# Business Insights – Credit Card Financial Analysis

This document summarizes key insights derived from the Power BI dashboards created for the Credit Card Financial Analysis project. The insights are based on weekly transaction and customer data.

---

## 📊 Transaction-Based Insights

- Certain credit card categories like Blue contribute significantly higher revenue compared to others like silver, gold and platinum, indicating that blue card type play a major role in revenue generation.
- High transaction volume does not always result in higher revenue, as transaction value and interest earned vary across card categories.
- Interest earned contributes a noticeable portion of total revenue, highlighting the importance of credit utilization behavior.
- Weekly revenue trends help identify performance fluctuations and can be used to monitor short-term financial changes.
- Customers who are businessmen are contributing the most to the revnue over others whereas retired customers are the least revenue generating ones.
- Gradutes are contributing the most to the revenue over other educated people whereas doctorate and PG ones are the least revenue generating customers.
- Customer who use swipe card method are contributing the most to the revenue ove other card methods.

---

## 👥 Customer-Based Insights

- Customers from specific income groups which lie in the High Category (more than 75K per month) generate the highest share of total revenue, indicating strong correlation between income level and spending behavior.
- Customers belonging to 40-60 years are contributing the most to the total revenue describing our main customers to focus on based on age group.
- Revenue contribution varies weekly which can help identifying the business weeks and months.
- Customers who have 2-3 dependent people are contributing the most to the total revenue.
- Top revenue generating states help to identify the regions contributing to the revenue the most.

---

## 📈 Business Value of the Analysis

- The dashboards enable stakeholders to monitor weekly financial performance efficiently.
- Insights can help financial institutions optimize credit card offerings and marketing strategies.
- Identifying high-revenue customer segments supports better decision-making and personalized services.
- Regular refresh of dashboards ensures updated insights as new data becomes available.

---

## 🔄 Data Refresh Validation

After generating the dashboards, additional records were inserted into the MySQL database to simulate new weekly data. Upon refreshing Power BI, the dashboards updated automatically, confirming the reliability of the data pipeline and refresh mechanism.
