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

✔️ Shift Toward Costly Shipping Methods:
There was an increase in order volume using high-cost shipping methods, especially First Class (+33%) and Same Day (+25%), which led to faster growth in shipping expenses than in gross profit.

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
- Source: Kaggle  
- Size:
  - The Orders table contains 51,290 records
  - The People table contains 13 records
  - The Returns table contains 1,172 records  
- Format: .csv  

### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used:  
The dataset consists of three tables:  
- Orders – Contains detailed transaction and customer information
<details>
<summary><strong>📊 Table 1: Orders</strong></summary>

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
- Returns – Stores data on returned orders.  
<details>
<summary><strong>📦 Table 2: Returns</strong></summary>

| Column Name | Data Type | Description                                           |
|-------------|-----------|-------------------------------------------------------|
| Returned    | VARCHAR   | Indicates whether the order was returned (e.g., 'Yes' or 'No'). |
| Order ID    | VARCHAR   | Unique identifier for each order.                    |

</details>

- People – Holds information about sales representatives.
<details>
<summary><strong>🧑‍💼 Table 3: People</strong></summary>

| Column Name | Data Type | Description                                           |
|-------------|-----------|-------------------------------------------------------|
| Person      | VARCHAR   | Name of the salesperson.                             |
| Region      | VARCHAR   | Geographic region where the salesperson operates.    |

</details>

#### 2️⃣ Data Relationships:  

![image](https://github.com/user-attachments/assets/e16fece0-207e-48c9-81f4-ce7f92fc9958)


## 🧠 Design Thinking Process  

Explain the step-by-step approach taken to solve the problem.  

👉🏻 Insert a screenshot of the Design Thinking steps (Screenshot your Excel design thinking tables for better presentation).  

1️⃣ Empathize  

![image](https://github.com/user-attachments/assets/0d266023-7860-4faa-8e0b-9d7d63a0789e)
![image](https://github.com/user-attachments/assets/0263534c-443f-42cf-8f3e-6d9ff752c977)  

2️⃣ Define point of view  

![image](https://github.com/user-attachments/assets/01c1e607-acef-4da6-839b-74ef092edd69)  

3️⃣ Ideate  

![image](https://github.com/user-attachments/assets/2478ca06-3795-4549-bb80-051f23aee05a)

4️⃣ Prototype and review  

This part is in the dashboard

---

## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Overview 

![image](https://github.com/user-attachments/assets/ad0862a1-f30d-459d-8344-fa3a65757af8)  

Từ năm 2011 đến 2014, công ty duy trì tốc độ tăng trưởng tốt về doanh thu và lợi nhuận. Riêng năm 2014, doanh thu tiếp tục tăng mạnh (+24% so với 2013). Tuy nhiên, biên lợi nhuận (Profit Margin) lại có dấu hiệu giảm nhẹ trên cả ba thị trường chính (APAC, EU, US), phản ánh một số vấn đề về hiệu quả sinh lời.  

![1](https://github.com/user-attachments/assets/be44600c-98c9-47d7-9c5d-aa8d50263cfc)


📌 Analysis:  

  📈 Doanh thu tăng nhưng lợi nhuận không theo kịp
Biên lợi nhuận cao nhất xuất hiện ở năm 2013 (11.97%), không phải năm có doanh thu cao nhất (2014). Điều này phản ánh rằng khi doanh thu tăng, chi phí cũng tăng theo—có thể là dấu hiệu công ty đang đánh đổi margin để mở rộng quy mô.

🚚 Gia tăng đơn hàng qua các phương thức giao hàng chi phí cao
Trong năm 2014, công ty ghi nhận xu hướng gia tăng đơn hàng sử dụng các phương thức vận chuyển có chi phí cao như First Class và Same Day. Sự chuyển dịch này làm tăng chi phí logistics đáng kể, khiến tổng chi phí vận hành tăng nhanh hơn so với lợi nhuận gộp—góp phần làm suy giảm hiệu quả sinh lời.  

🛍️ Tỷ trọng nhóm hàng lợi nhuận thấp tăng lên
Đặc biệt, nhóm Office Supplies—dù có biên lợi nhuận thấp—lại ghi nhận lượng đơn hàng tăng mạnh trong năm 2014. Sự gia tăng này khiến cơ cấu sản phẩm dịch chuyển theo hướng kém lợi nhuận hơn, làm ảnh hưởng đến biên lợi nhuận toàn doanh nghiệp.  

![2](https://github.com/user-attachments/assets/826e0533-f500-446f-8e68-1987362e13d3)

🔁 Tỷ lệ hoàn trả tăng nhẹ tại APAC và US
So với 2013, năm 2014 ghi nhận tỷ lệ hoàn trả tăng ở các thị trường lớn như APAC (4.99% → 5.04%) và US (5.90% → 6.12%). Mức tăng tuy nhỏ, nhưng khi kết hợp với chi phí vận chuyển cao và cơ cấu hàng hóa kém tối ưu, nó góp phần làm giảm doanh thu ròng và tăng chi phí xử lý.  

![3](https://github.com/user-attachments/assets/9509d04d-c6b4-4c28-bca9-6d7f80448e78)

⚠️ Tổng hợp ba yếu tố khiến biên lợi nhuận suy giảm
Việc giảm Profit Margin năm 2014 không đến từ một yếu tố đơn lẻ mà là hệ quả của:  

(1) tăng tỷ lệ sử dụng ship đắt tiền  

(2) tỷ trọng nhóm hàng lời thấp tăng  

(3) tỷ lệ hoàn trả tăng.
→ Tất cả kết hợp lại gây áp lực lớn lên chi phí và bào mòn lợi nhuận.  

🌍 EU – doanh thu cao nhưng return rate cao nhất (6.18%)
Mặc dù EU là một trong những thị trường lớn nhất về doanh thu và lợi nhuận, nhưng lại có tỷ lệ hoàn trả cao nhất toàn hệ thống. Đây là dấu hiệu cảnh báo về chất lượng sản phẩm, dịch vụ hậu mãi hoặc trải nghiệm khách hàng chưa tốt. Nếu không cải thiện, điều này sẽ tiếp tục ảnh hưởng tới lợi nhuận dài hạn.

🪑 Furniture – danh mục sản phẩm yếu kém
Trong 3 nhóm chính (Technology, Office Supplies, Furniture), nhóm Furniture ghi nhận lợi nhuận thấp nhất. Rất có thể danh mục này được giữ lại vì mục tiêu đa dạng hóa, nhưng trên thực tế đang kéo hiệu suất tổng thể đi xuống.  

💡 Recommendation:

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


