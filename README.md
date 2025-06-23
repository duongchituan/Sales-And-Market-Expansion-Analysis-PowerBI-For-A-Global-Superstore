# 📊 Sales Performance & Market Expansion For A Global Superstore | Power BI

---
![ChatGPT Image 13_27_57 23 thg 6, 2025](https://github.com/user-attachments/assets/2bb232ae-9c85-4725-8079-4247c7cd9f37)


Author: Duong Chi Tuan  
Date: May 2025  
Tools Used: Power BI  

---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)  
3. [🧠 Design Thinking Process](#-design-thinking-process)  
4. [📊 Key Insights & Visualizations](#-key-insights--visualizations)  
5. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? 
 
This project provides a Power BI dashboard to support strategic decision-making. The objective is:  

- Understand company-wide sales performance

- Identify top products & regions for market expansion

- Support senior management in selecting strategic products 

### 👤 Who is this project for?  

✔️ Senior managers & business decision-makers  

✔️ Strategy teams exploring market expansion  

✔️ Product managers evaluating performance  

✔️ Data analysts supporting executive insights  

###  ❓Business Questions:  
✔️ Which products generate the most revenue and profit?  

✔️ What are the top-performing regions or markets?  

✔️ Which customer segments are the most valuable?  

✔️ Are there markets with growth potential we haven’t tapped into yet?  

✔️ What trends can inform our product and market expansion strategies?  

### 🎯Project Outcome:  
✔️ Profit Margin Decline in 2014:
Despite a strong revenue increase (+24% vs. 2013), the company experienced a slight drop in overall profit margin (from 11.97% to 11.51%) due to rising operational costs.

✔️ Higher Usage of Expensive Shipping Modes:
Orders shipped via First Class rose by +33% (from 2.4K to 3.2K) and Same Day by +25% (from 0.8K to 1.0K), particularly within the Office Supplies category—putting downward pressure on profitability.

✔️ Suboptimal Product Mix Impacting Margins:
The surge in Office Supplies orders—typically low-margin products—combined with costly shipping methods, contributed to the margin decline.

✔️ Return Rate Remained Stable:
Return rates in key markets (APAC, EU, US) remained steady (around 5–7%) and were not a major driver of profit decline.

✔️ High-Margin Niche Market Identified:
Canada, though a small market (Revenue: 0.05M), achieved the highest profit margin (27.59%), with Copiers contributing 38% of total profit—highlighting a highly efficient product-market fit.

✔️ Expansion Opportunity Identified:
Recommend a targeted expansion into Canada, focusing on high-margin products like Copiers, while avoiding scale-up of low-margin categories such as Office Supplies.  

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- Source: (Mention where the dataset is obtained from—Kaggle, company database, government sources, etc.)  
- Size: (Mention the number of rows & columns)  
- Format: (.csv, .sql, .xlsx, etc.)  

### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used:  
Mention how many tables are in the dataset.  

#### 2️⃣ Table Schema & Data Snapshot  

Table 1: Products Table  

👉🏻 Insert a screenshot of table schema 

 _Example:_

| Column Name | Data Type | Description |  
|-------------|----------|-------------|  
| Product_ID  | INT      | Unique identifier for each product |  
| Name        | TEXT     | Product name |  
| Category    | TEXT     | Product category |  
| Price       | FLOAT    | Price per unit |  



Table 2: Sales Transactions  

👉🏻 Insert a screenshot of table schema 


 _Example:_

| Column Name    | Data Type | Description |  
|---------------|----------|-------------|  
| Transaction_ID | INT      | Unique identifier for each sale |  
| Product_ID     | INT      | Foreign key linking to Products table |  
| Quantity       | INT      | Number of items sold |  
| Sale_Date      | DATE     | Date of transaction |  


📌If the table is too big, only capture a part of it that contains key metrics you used in the projects or put the table in toggle

#### 3️⃣ Data Relationships:  
Describe the connections between tables—e.g., one-to-many, many-to-many.  

👉🏻 Include a screenshot of Data Modeling to visualize relationships.  

---

## 🧠 Design Thinking Process  

Explain the step-by-step approach taken to solve the problem.  

👉🏻 Insert a screenshot of the Design Thinking steps (Screenshot your Excel design thinking tables for better presentation).  

1️⃣ Empathize  
2️⃣ Define point of view  
3️⃣ Ideate  
4️⃣ Prototype and review  

---

## ⚒️ Main Process

1️⃣ Data Cleaning & Preprocessing  
2️⃣ Exploratory Data Analysis (EDA)  
3️⃣ SQL/ Python Analysis 

- In each step, show your Code

- Include query/ code execution screenshots or result samples

- Explain its purpose and its findings


4️⃣ Power BI Visualization  (applicable for PBI Projects)

---

## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Dashboard 1 Preview  
👉🏻 Insert Power BI dashboard screenshots here  

📌 Analysis 1:  
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

#### 2️⃣ Dashboard 2 Preview  
👉🏻 Insert Power BI dashboard screenshots here

📌 Analysis 2:   
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

#### 3️⃣ Dashboard 3 Preview  
👉🏻 Insert Power BI dashboard screenshots here  

📌 Analysis 3:  
- Observation: _Describe trends, key metrics, and patterns._  
- Recommendation: _Suggest actions based on insights._  

---

## 🔎 Final Conclusion & Recommendations  

👉🏻 Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:  

📌 Key Takeaways:  
✔️ Recommendation 1  
✔️ Recommendation 2  
✔️ Recommendation 3
