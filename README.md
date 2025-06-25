# 📊 Customer Purchase Behavior and Sentiment Analysis

This repository hosts a comprehensive **end-to-end analytics project** that combines structured customer transaction data with unstructured customer review data to analyze **purchase behavior** and **sentiment insights**. The goal is to empower businesses with **emotionally intelligent**, **data-driven decisions**—aligning with purpose-led strategies like those of Aaruchudar.

---

## 🎯 Project Objective

The primary objective is to:
- Identify trends and patterns in customer purchase behavior.
- Analyze customer sentiment based on product reviews.
- Provide insights to guide marketing, product development, and customer engagement.

---

## 📦 Datasets Used

### 1. Customer Purchase Data

| Field            | Description                          |
|------------------|--------------------------------------|
| Transaction ID   | Unique ID for each purchase          |
| Customer ID      | Unique customer identifier           |
| Customer Name    | Name of the customer                 |
| Product ID       | ID of the purchased product          |
| Product Name     | Name of the product                  |
| Product Category | Category to which the product belongs|
| Purchase Quantity| Number of units purchased            |
| Purchase Price   | Unit price                           |
| Purchase Date    | Date of transaction                  |
| Country          | Customer’s country                   |

### 2. Customer Reviews Data

| Field        | Description                        |
|--------------|------------------------------------|
| Review ID    | Unique ID for each review          |
| Customer ID  | Reviewer’s customer ID             |
| Product ID   | Reviewed product ID                |
| Review Text  | Text of the customer review        |
| Review Date  | Date of the review                 |

---

## 🔍 Key Features

### 1. Data Extraction & Transformation (SQL)
- Designed a MySQL relational database schema.
- Created SQL scripts for data ingestion and transformation.
- Cleaned and normalized data to ensure consistency.
- Generated metrics such as:
  - Total purchases and revenue by customer
  - Total sales by product/category
  - Time-based purchasing trends

### 2. Data Analysis (Python)
- Connected MySQL database with Python using `pymysql`.
- Performed **sentiment analysis** on reviews using `TextBlob`.
- Categorized reviews as **Positive**, **Neutral**, or **Negative**.
- Generated visual insights using `matplotlib` and `seaborn`:
  - Purchase trends over time
  - Sentiment distribution across products
  - Top customers and product categories

### 3. Data Visualization (Power BI)
- Built an **interactive Power BI dashboard** showcasing:
  - Time-based purchase trends
  - Customer segmentation
  - Product/category performance
  - Sentiment breakdown by product/category
- Enabled filtering by:
  - Product category
  - Customer group
  - Time period

---

## 🧰 Tools & Technologies

- **Database:** MySQL  
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, TextBlob, matplotlib, seaborn, pymysql  
- **Visualization Tool:** Power BI Desktop

---

## 📂 Project Structure

├── data/
│ ├── customer_purchase_data.csv
│ ├── customer_reviews_data.csv
│ ├── updated_reviews_data.csv
├── sql/
│ ├── cust_pur_details.sql
├── notebooks/
│ ├── Customer Purchase Behavior and Sentiment Analysis.ipynb
├── dashboard/
│ ├── Ecommerce Analytics Dashboard.pbix
├── README.md

## 📈 Results and Insights
📊 Purchase Trends: Monthly and yearly purchase patterns

👤 Top Customers: High-value customer behavior insights

📦 Product Performance: Best-selling categories and products

💬 Sentiment Analysis: Emotional responses from customers by product/category

🧠 Human Intelligence Focus: Integrating behavior and sentiment for strategic decisions
