# 📊 Sales & Market Expansion Analysis For A Global Superstore (PowerBI)

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
4. [📊 Key Insights & Visualizations & Recommendations](#-key-insights--visualizations)  

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

✔️ Data analysts supporting executive insights  

###  ❓Business Questions:  
✔️ Which products generate the most revenue and profit?  

✔️ What are the top-performing regions or markets?  

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- Source: Kaggle  
- Size:
  - The Orders table contains 51,290 records
  - The People table contains 13 records
  - The Returns table contains 1,172 records  
- Format: .csv  

### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used:  
The dataset consists of three tables:  
<details>
<summary><strong>📊 Table 1: Orders - Contains detailed transaction and customer information</strong></summary>

| Column Name     | Data Type | Description                                         |
|-----------------|-----------|-----------------------------------------------------|
| Order ID        | VARCHAR   | Unique identifier for each order.                  |
| Order Date      | DATE      | Date when the order was placed.                   |
| Ship Date       | DATE      | Date when the order was shipped.                  |
| Ship Mode       | VARCHAR   | Shipping method used for delivery.                |
| Customer ID     | VARCHAR   | Unique identifier for each customer.              |
| Customer Name   | VARCHAR   | Full name of the customer.                        |
| Segment         | VARCHAR   | Customer segment (e.g., Consumer, Corporate).     |
| City            | VARCHAR   | City where the order was placed.                  |
| State           | VARCHAR   | State where the order was placed.                 |
| Country         | VARCHAR   | Country where the order was placed.               |
| Postal Code     | VARCHAR   | Postal code of the shipping address.              |
| Market          | VARCHAR   | Market region (e.g., APAC, EMEA).                 |
| Region          | VARCHAR   | Geographical region of the order.                 |
| Product ID      | VARCHAR   | Unique identifier for each product.               |
| Category        | VARCHAR   | Product category (e.g., Furniture, Office Supplies). |
| Sub-Category    | VARCHAR   | Sub-category of the product.                      |
| Product Name    | VARCHAR   | Name of the product ordered.                      |
| Sales           | DECIMAL   | Revenue generated from the order.                 |
| Quantity        | INT       | Number of items ordered.                          |
| Profit          | DECIMAL   | Profit earned from the order.                     |

</details>
<details>
<summary><strong>📦 Table 2: Returns – Stores data on returned orders</strong></summary>

| Column Name | Data Type | Description                                           |
|-------------|-----------|-------------------------------------------------------|
| Returned    | VARCHAR   | Indicates whether the order was returned (e.g., 'Yes' or 'No'). |
| Order ID    | VARCHAR   | Unique identifier for each order.                    |

</details>

<details>
<summary><strong>🧑‍💼 Table 3: People – Holds information about sales representatives</strong></summary>

| Column Name | Data Type | Description                                           |
|-------------|-----------|-------------------------------------------------------|
| Person      | VARCHAR   | Name of the salesperson.                             |
| Region      | VARCHAR   | Geographic region where the salesperson operates.    |

</details>

#### 2️⃣ Data Relationships:  

![image](https://github.com/user-attachments/assets/e16fece0-207e-48c9-81f4-ce7f92fc9958)


## 🧠 Design Thinking Process  

Explain the step-by-step approach taken to solve the problem.  

1️⃣ Empathize  

![image](https://github.com/user-attachments/assets/9a174114-56d7-4db5-908c-f8bc29458b63)

![image](https://github.com/user-attachments/assets/a1c30bda-9210-452c-ae6a-a097c89332d8)


2️⃣ Define point of view  

![image](https://github.com/user-attachments/assets/f8095e2f-de5a-4c4e-9544-2c587495725b)

3️⃣ Ideate  

![image](https://github.com/user-attachments/assets/3c861a6a-e804-44dc-85d5-6bc33c65d1b1)

![image](https://github.com/user-attachments/assets/5f7e537a-a3a5-405c-abf2-ec70395024c1)

---

## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Region 

![image](https://github.com/user-attachments/assets/64522d82-c85e-4cdd-8af5-73191d5bc5be)  

📌 Analysis:  

- Total revenue reached $9.48M with a total profit of $1.09M. The average return rate is 4.68%, and the overall ROI is 13%. While the company is operating profitably overall, regional performance varies significantly and highlights clear areas for optimization and expansion.  

- The Central region generated the highest revenue ($2.07M) but only moderate ROI, with a return rate of 4.79%. This suggests potential inefficiencies in cost structure or operations. Regions like South and North show stable performance with decent revenue and ROI — current strategy can be maintained.

- In contrast, Canada and North Asia stand out with very high ROI (38.1% and 24%, respectively). Canada, though small in current revenue, presents a high-growth opportunity and should be prioritized for expansion. North Asia also shows strong profitability, but the return rate is high (13.83%), indicating issues with product quality, expectations, or logistics — which need to be resolved before scaling further.

- Southeast Asia and EMEA deliver low ROI and minimal profit, suggesting a mismatch between product-market fit or operational inefficiencies. Investment in these regions should be limited or re-evaluated unless performance improves.

💡 Recommendation:  

- Expand into high-ROI regions: Prioritize Canada and North Asia (with return rate improvements).

- Optimize cost & return rate in high-revenue regions like Central.

- Maintain steady operations in South, North, and West.

- Limit further investment in Southeast Asia and EMEA until performance metrics improve.

#### 2️⃣ Dashboard 2 Preview  

![image](https://github.com/user-attachments/assets/99ef0e14-bbe6-4077-8bea-da71d6bc5f88)

📌 Analysis:   

- Total revenue reached $9.48M with a total profit of $1.09M and an average profit margin of 11.5%. The overall product return rate is 4.68%.  

- Top revenue products include Phones ($1.38M), Copiers ($1.25M), and Chairs/Bookcases ($1.2M).

- Highest profit contributors are Copiers ($0.22M), Phones ($0.18M), and Bookcases ($0.13M) — showing both strong sales and good margins.

- In terms of ROI, Technology (16.98%) and Office Supplies (15.41%) outperform Furniture (7.12%).

- Products with high return rates include Tables (7.28%), Appliances (5.92%), and Accessories (5.72%).

- Products with low return rates include Art (3.15%), Binders (3.61%), and Labels (3.75%).  

⭐ Based on revenue, profit, ROI, and return rate, the following are recommended as strategic products:

- Copiers: High revenue and profit, strong ROI, moderate return rate. Falls under the high-performing Technology category.

- Phones: Highest revenue, decent profit, acceptable return rate. Great potential for market expansion.

- Bookcases / Chairs: Consistent performance, but ROI can be improved through cost control (Furniture category).

- Binders / Labels: Low-volume but low-return-rate products with stable margins — suitable for B2B or bulk-sale strategies.

💡 Recommendation:  

- Focus on Technology and Office Supplies categories due to high ROI and strong profitability. Prioritize products like Copiers and Phones for strategic growth.

- Reduce return rates for high-potential items like Tables and Appliances by improving product quality, descriptions, and customer experience.

- Review underperforming products with low profit and high return rates for possible repositioning or phase-out.

- Consider scaling stable niche products like Binders and Labels through bundled offers or business-targeted campaigns.




---


