# Brazilian E-Commerce Data Analysis Project

This repository contains the workflow and insights derived from analyzing a Brazilian e-commerce dataset. The project demonstrates the complete data analysis pipeline, from raw data collection to insightful visualizations using **Power BI**.

--- 
## Introduction

The Brazilian e-commerce market is one of the fastest-growing sectors in Latin America, driven by increasing internet penetration and consumer demand for online shopping. To better understand this dynamic industry, this project analyzes a comprehensive dataset of e-commerce transactions from Brazil. 

The analysis covers multiple aspects, including sales trends, shipping cost efficiency, customer behavior, and seller performance. By leveraging tools such as **MySQL** and **Power BI**, the project aims to provide actionable insights that can drive better decision-making for businesses operating in the e-commerce domain. 

This repository documents the entire journey, from raw data preprocessing to dashboard creation, showcasing the data-driven approach to uncover meaningful patterns and trends.

---

## Table of Contents

1. [Goals and Key Questions](#goals-and-key-questions)
2. [Data Sources](#data-sources)
3. [Tools and Technologies](#tools-and-technologies)
4. [Project Workflow](#project-workflow)
5. [Dashboards and Key Insights](#dashboards-and-key-insights)
   - [Sales Analysis](#sales-analysis)
   - [Shipping Cost Analysis](#shipping-cost-analysis)
   - [Order Lifecycle & Delivery Performance](#order-lifecycle--delivery-performance)
   - [Customer Insights](#customer-insights)
   - [Sellers Evaluation](#sellers-evaluation)
   - [Business Overview and Summary](#business-overview-and-summary)
6. [Recommendations and Future Plans](#recommendations-and-future-plans)

---

## Goals and Key Questions

### Goals:
- To understand and visualize sales, customer behavior, and logistics for Brazilian e-commerce businesses.
- To generate actionable insights for optimizing business operations.

### Key Questions:
1. What are the sales trends across time, categories, and regions?
2. How does shipping cost vary by region and distance?
3. What is the lifecycle of an order, and how can delivery performance be improved?
4. Who are the most valuable customers and sellers?
5. What operational KPIs can summarize overall business health?

---

## Data Sources

- [Kaggle: Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Data transformations and preprocessing were performed using Excel and SQL.

---

## Tools and Technologies

- **Microsoft Excel**: Data cleaning and preparation.
- **Notepad++**: Plugin development for CSV-to-SQL conversion.
- **MySQL**: Database management and advanced SQL queries.
- **Power BI**: Data visualization and dashboard creation.

---

## Project Workflow

1. **Data Acquisition**: Downloaded raw data from Kaggle.
2. **Data Cleaning**: Processed and organized the data in Excel.
3. **Data Transformation**:
   - Converted data into SQL format using a Notepad++ plugin.
   - Uploaded data to MySQL for further processing.
4. **Data Manipulation**:
   - Created calculated columns such as distance from São Paulo and average shipping cost.
   - Standardized state abbreviations into full names.
   - Executed advanced SQL queries for analysis preparation.
5. **Data Visualization**:
   - Connected MySQL database to Power BI.
   - Ensured accurate data relationships in Power BI modeling.
   - Built six interactive dashboards.

---

## Dashboards and Key Insights

### 1. Sales Analysis

**Key Insights**:
- Health & Beauty was the top-performing product category, contributing over 9% of total sales.
- São Paulo led sales across states, reflecting its strong customer base and market size.
- Monthly sales peaked in July 2017, driven by seasonal promotions.

**Dashboard Preview**:  
*(Insert image here)*

---

### 2. Shipping Cost Analysis

**Key Insights**:
- Average shipping cost increased with distance from São Paulo, highlighting logistical challenges.
- São Paulo accounted for the highest shipping cost, reflecting its high order volume.
- A direct correlation between shipping cost and product size was observed.

**Dashboard Preview**:  
*(Insert image here)*

---

### 3. Order Lifecycle & Delivery Performance

**Key Insights**:
- The average delivery time across all states was 12.5 days, with significant delays in remote regions like Amapá.
- Over 92% of orders were delivered on time, meeting the defined SLA.
- States closer to São Paulo experienced faster delivery times.

**Dashboard Preview**:  
*(Insert image here)*

---

### 4. Customer Insights

**Key Insights**:
- New customers constituted 93% of the total base, indicating strong acquisition strategies.
- Customer lifetime value (CLV) was highest among repeat buyers, emphasizing the importance of retention.
- Most customers preferred credit card payments, accounting for 74% of transactions.

**Dashboard Preview**:  
*(Insert image here)*

---

### 5. Sellers Evaluation

**Key Insights**:
- São Paulo sellers contributed the most revenue, followed by Paraná and Minas Gerais.
- Top-performing sellers accounted for over 10% of total sales, indicating a small number of highly successful sellers.
- Seller distribution aligned closely with customer density across states.

**Dashboard Preview**:  
*(Insert image here)*

---

### 6. Business Overview and Summary

**Key Insights**:
- Total revenue from 112,650 orders exceeded 15.8M BRL.
- Average order value stood at 120.65 BRL, with consistent growth over time.
- Over 99,000 unique customers were served, demonstrating extensive reach.

**Dashboard Preview**:  
*(Insert image here)*

---

## Recommendations and Future Plans

### Recommendations:
1. **Optimize Shipping Costs**: Implement regional warehouses to minimize shipping distances and costs.
2. **Enhance Customer Retention**: Develop loyalty programs to convert new customers into repeat buyers.
3. **Focus on Delivery Times**: Improve logistics in remote regions to reduce delivery delays and boost customer satisfaction.
4. **Seller Performance Monitoring**: Provide targeted support to underperforming sellers to increase overall sales.

### Future Plans:
- **Predictive Analytics**: Integrate machine learning models to forecast sales and logistics requirements.
- **Real-Time Dashboards**: Enable live data updates in Power BI for ongoing monitoring.
- **Market Expansion Analysis**: Use the dataset to explore potential market expansion opportunities.

---

## Author

- [Ahmed Moustafa Kamal](https://github.com/ahmedmoustafa31)  
  Data Analyst and Business Intelligence Developer

