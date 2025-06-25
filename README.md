# 📊 Customer Purchase Behavior and Sentiment Analysis
This repository hosts a comprehensive end-to-end analytics project that combines structured customer transaction data with unstructured customer review data to analyze purchase behavior and sentiment insights. The goal is to empower businesses with emotionally intelligent, data-driven decisions—aligning with purpose-led strategies like those of Aaruchudar.

🎯 Project Objective
The primary objective is to:

Identify trends and patterns in customer purchase behavior.

Analyze customer sentiment based on product reviews.

Provide insights to guide marketing, product development, and customer engagement.

📦 Datasets Used
1. Customer Purchase Data
| Field             | Description                           |
| ----------------- | ------------------------------------- |
| Transaction ID    | Unique ID for each purchase           |
| Customer ID       | Unique customer identifier            |
| Customer Name     | Name of the customer                  |
| Product ID        | ID of the purchased product           |
| Product Name      | Name of the product                   |
| Product Category  | Category to which the product belongs |
| Purchase Quantity | Number of units purchased             |
| Purchase Price    | Unit price                            |
| Purchase Date     | Date of transaction                   |
| Country           | Customer’s country                    |


2. Customer Reviews Data
| Field       | Description                 |
| ----------- | --------------------------- |
| Review ID   | Unique ID for each review   |
| Customer ID | Reviewer’s customer ID      |
| Product ID  | Reviewed product ID         |
| Review Text | Text of the customer review |
| Review Date | Date of the review          |


🔍 Key Features
1. Data Extraction & Transformation (SQL)
MySQL database schema for relational modeling.

Data ingestion and normalization using SQL.

Advanced queries for metrics like:

Total sales by product/customer

Monthly/quarterly purchase trends

High-value customer identification

2. Data Analysis (Python)
Data pulled from MySQL using pymysql

Sentiment classification using TextBlob

Positive, Neutral, Negative labels

Metrics derived:

Purchase frequency

Revenue trends

Sentiment distribution by product/category

3. Data Visualization (Power BI)
Dynamic and interactive Power BI dashboard

Key visuals include:

Monthly/yearly purchase trends

Customer segmentation

Top products by revenue/volume

Sentiment analysis dashboard

🧰 Tools & Technologies
Database: MySQL

Languages: Python

Libraries: pandas, numpy, TextBlob, matplotlib, seaborn, pymysql

Visualization: Power BI Desktop

📂 Project Structure
pgsql
Copy
Edit
├── data/
│   ├── customer_purchase_data.csv
│   ├── customer_reviews_data.csv
│   ├── updated_reviews_data.csv
├── sql/
│   ├── cust_pur_details.sql
├── notebooks/
│   ├── Customer Purchase Behavior and Sentiment Analysis.ipynb
├── dashboard/
│   ├── Ecommerce Analytics Dashboard.pbix
│   ├── Ecommerce Analytics Dashboard.pdf
├── README.md



📈 Results and Insights
Purchase Trends: Seasonal patterns in customer activity

Top Customers: Behavioral and financial segmentation

Product Performance: Best-performing products/categories

Sentiment Analysis: Customer emotions and their effect on sales

Human-Centered Intelligence: Emotion-infused decision-making for business growth
