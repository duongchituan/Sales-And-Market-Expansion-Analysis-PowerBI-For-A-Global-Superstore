# 📊 Sales and Market Expansion Analysis for a Global Retailer of Office Supplies, Furniture, and Technology (Power BI)

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
 
This project delivers a **Power BI dashboard** built using sales data from Superstore, a retail company with a diverse product portfolio. The core objective is to support senior management in making strategic decisions, particularly in two key areas: **market expansion** and **product selection**.  

🔍 By analyzing company-wide sales and profit data, the dashboard helps address critical business questions such as:

- Which products generate the highest **revenue** and **profit**?
- Which regions or markets are performing best?
- Are there underperforming areas or **growth opportunities** that need attention?

💡 The dashboard provides leadership with the insights needed to:

- Identify **high-potential markets** for expansion  
- Select **strategic products** to prioritize for growth  
- Monitor trends over time and evaluate performance by region and product line  
- Align decisions with real-time data to drive effective, long-term growth  

Ultimately, this project equips Superstore’s leadership with a clear, **data-driven foundation** to craft **expansion strategies** and make informed product decisions.


### 👤 Who is this project for?  

✔️ Senior managers & business decision-makers  

✔️ Data analysts supporting executive insights  

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

<img width="1309" height="802" alt="image" src="https://github.com/user-attachments/assets/4c4055f9-ef35-4391-8129-3bf0ca257718" />

📌 Analysis:  

1️⃣ Overall performance:  

- **Revenue** reached **$3.21M** (+24.41% compared to 2013), and **profit** was **$369.74K** (+19.56%), indicating strong revenue growth but slower profit growth.
  
- **ROI** decreased to **13%** (↓4.41%), reflecting lower investment efficiency or rising costs.
  
- **Return rate** dropped significantly to **4.55%** (↓3.57% vs. 2013), suggesting improvements in product quality or customer experience, contributing to lower logistics costs and better operational efficiency.

2️⃣ Time trend:  

- **Revenue** increased steadily from 2011 to 2014.
  
- **Profit margin** remained relatively flat, fluctuating between **11–12%**, indicating that revenue growth did not lead to higher profitability.
3️⃣ Regional performance:  

- **Central**: Largest revenue (**$2.07M**) and highest profit (**$212K**), lowest return rate (**4.8%**), ROI **10.3%** → _Stable, large-scale, low risk_.
  
- **South**: Revenue **$1.18M**, profit **$100K**, return rate **3.8%**, ROI **15.8%** → _Efficient and scalable_.
  
- **North**: Profit **$148K**, ROI **14.2%**, return rate **10%** → _Acceptable risk with strong profitability_.
  
- **North Asia (China)**: ROI **26.9%**, profit **$110K**, return rate **13.3%** → _Very high efficiency with manageable risk_.
  
- **Central Asia (India)**: Revenue **$4.12M**, profit **$95.5K**, return rate **2.3%**, but ROI only **2.3%** → _Margin/cost structure needs improvement_.
  
- **Southeast Asia, East, Africa, Oceania**: ROI between **11–13.6%**, return rate <4%, revenue modest → _Potential with further development_.
  
- **West, EMEA**: ROI <9%, return rate >10% → _Not optimal for scaling_.
  
- **Canada, Caribbean**: Zero profit and ROI, very low revenue → _Not viable at this stage_.

💡 Recommendation:  

🔵 **Prioritize expansion in:**
- **Central**: Most stable and profitable region with low return rate → continue investment and improve ROI via cost control.
  
- **South**: High ROI, low return rate, and scalable → optimize operations for higher return.
  
- **North**: Strong profit and ROI, manageable return rate → suitable for parallel expansion.
  
- **North Asia (China)**: Excellent ROI and profit; return rate now under control → strong candidate for strategic expansion.

🟡 **Consider conditional expansion in:**
- **Central Asia (India)**: Low return rate, large revenue base, but ROI is low → expand only after addressing cost/margin inefficiencies.
  
- **Southeast Asia, East, Africa, Oceania**: Promising ROI and low return rate, but smaller scale → test further with controlled investment.

🔴 **Do not expand now in:**
- **West, EMEA**: High return rate and low ROI → not cost-effective for growth.
  
- **Canada, Caribbean**: No profitability, low revenue, and zero ROI → unsuitable for any expansion unless root issues are addressed.
#### 2️⃣ Product  

![image](https://github.com/user-attachments/assets/6910602c-1d6e-4a07-a487-7ec85d06de45)

📌 Analysis:   

- Top revenue-generating products include Phones ($1.38M), Copiers ($1.25M), and Chairs/Bookcases (each $1.20M). In terms of profitability, Copiers lead with $0.22M, followed by Phones ($0.18M) and Bookcases ($0.13M). These products not only deliver high revenue but also maintain solid profit margins, indicating strong potential for long-term sustainability and further expansion.  

- However, several product lines are experiencing unusually high return rates, such as Tables (174.15%), Fasteners (152.01%), and Labels (135.18%). These figures point to serious risks related to product quality or after-sales service processes. In contrast, Phones (44.24%), Chairs (52.36%), and Bookcases (60.54%) show relatively low return rates, suggesting these are more stable and reliable products, less likely to incur extra return or customer service costs.  

- Products positioned in the "high revenue – high profit" quadrant — such as Copiers, Phones, Bookcases, and Chairs — are strategic lines that should continue to be prioritized and strengthened. On the other hand, product lines like Fasteners, Supplies, Furnishings, and Labels, which fall into the "low revenue – low profit" zone, should be carefully reviewed for optimization or even removal if necessary.  

- Although smartphones top the revenue chart, they suffer from an extremely high return rate (over 2000%), significantly impacting their actual profitability. Meanwhile, underperforming items such as Avery Binder Labels, Push Pins, and Eureka Bags are experiencing severe losses with return rates as high as 117,200%, indicating no remaining business value and should be considered for elimination.  

💡 Recommendation:  

1. Prioritize Strategic Product Lines
Focus on investing in and expanding high-performing products such as 🖨️ **Copiers**, 📱 **Phones**, 📚 **Bookcases**, and 🪑 **Chairs**.. These products significantly contribute to both **revenue** and **profit** while maintaining relatively **low and stable return rates**.

2. Improve Product Quality and After-Sales Processes
For products with ⚠️ **high return rates** such as **Tables**, **Fasteners**, and **Labels**, it's crucial to re-evaluate **product quality**, **packaging**, **product descriptions**, and **return policies** to reduce financial risks caused by excessive returns.

3. Optimize Product Portfolio
Products that fall into the 💸 **“low revenue – low profit”** zone, such as **Fasteners**, **Supplies**, and **Furnishings**, should be gradually phased out or repositioned in the market. This helps the company focus its resources on more profitable lines.

4. Warning on Phone Category
Although the 📱 **Phone category** generates the highest revenue, its extremely high return rate is significantly eroding actual profit. Stricter quality control, sourcing from more reputable suppliers, or improving after-sales service are necessary steps to prevent avoidable financial losses.




---


