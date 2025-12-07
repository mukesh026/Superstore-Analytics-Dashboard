# 📊 Superstore Analytics Project  


![Superstore Analytics Dashboard](/Images/Main.png)
  

🔗 <a href="https://app.powerbi.com/view?r=eyJrIjoiZjAwY2Y0ZDQtM2QzNi00MWFjLWE2MzMtMDVlNGI5ZjhkZDJlIiwidCI6IjE3ZDA1NDhhLTU2ZDYtNGY4NC05MWY3LTJjYTE5ZDgzM2Q4YyJ9" target="_blank">View the interactive dashboard on Power BI Service</a>


---

## 📑 Table of Contents  
1. [🔍 Overview](#-overview)  
2. [🗄️ Data Model](#️-data-model)  
3. [📊 Dashboard Features](#-dashboard-features)  
4. [🚀 Business Impact](#-business-impact)  
5. [🛠️ Tech Stack](#️-tech-stack)  
6. [📂 Project Structure](#-project-structure)  
7. [✨ Skills Demonstrated](#-skills-demonstrated)  
8. [📌 Future Improvements](#-future-improvements)  

---

## 🔍 Overview  
This project analyzes **Superstore sales data** using **Power BI** to uncover insights about sales, profit, customer returns, and performance across products, states, and segments.  

The interactive dashboard answers:  
- 📈 What are the total Sales, Profit, and % of Returned Orders? How do they compare YoY?  
- 📉 Which products drive profit vs loss?  
- 🌍 Which states contribute most profit or loss?  
- 🎯 How do customer segments perform?  

📂 Dashboard file: [`Superstore Analytics_Dashboard.pbix`](/Superstore%20Analytics%20Dashboard.pbix) 

📜 Dataset: [`Sample - Superstore.xls`](/Sample%20-%20Superstore.xls)  

 📂 [Dataset on Kaggle](https://www.kaggle.com/datasets/bitricks/superstore-dataset)

---

## 🗄️ Data Model  
The dataset includes three key tables:  

![Data Model](/Images/Data%20Model.png)

- **Orders** → Order details (Order ID, Product, Segment, State, Sales, Profit).  
- **Returns** → Returned orders (Order ID, Return Flag).  
- **Date** → Custom DAX date table (`CALENDAR`, `ADDCOLUMNS`) for time intelligence.  

**Relationships:**  
- Orders ↔ Returns (Order ID)  
- Orders ↔ Date (Order Date)  

📌 Star schema design ensures optimized analytics.  

---

## 📊 Dashboard Features  

### 🔹 KPI Cards (vs Previous Year) 

![KPI Cards](/Images/KPI.png)
 

### 🔹 Sales vs Previous Year Over Time  

![Sales vs Previous Year Over Time](Images//Sales%20vs%20Previous%20Year%20Over%20Time.png)


### 🔹 Profit by Product  

![Profit by Product](Images//Profit%20by%20Product.png)
 

### 🔹 Profitability by Geography  

![Profitability by Geography](Images//Profitability%20by%20Geography.png)
 

### 🔹 Segment Analysis  

![Segment Analysis](Images//Segment%20Analysis.png)


---

## 🚀 Business Impact  
This analysis empowers decision-makers to:  
- Monitor **YoY growth in sales & profit**.  
- Identify **loss-making products** to optimize.  
- Focus expansion on **high-profit states**.  
- Reduce **returns** for better customer satisfaction.  
- Align **strategies by customer segment**.  

---

## 🛠️ Tech Stack  
- **Power BI** → Dashboard visualization  
- **DAX** → Custom measures (YoY, % Returns, KPIs)  
- **Data Modeling** → Relationships & star schema  
- **Business Analytics** → KPI-driven decision making  

---


## ✨ Skills Demonstrated  
- 📊 Power BI Dashboarding & Storytelling  
- 📐 Data Modeling (Star Schema)  
- 🧮 DAX Calculations (YoY, % Returns, KPIs)  
- 🔎 Business Analytics & KPI tracking  
- 📝 Clear Insight Communication  

---

## 📌 Future Improvements  
- Add **customer-level analysis** (LTV, churn).  
- Build **forecasting models** using Power BI AI visuals.  
- Add **drill-through reports** for deeper product-level insights.  

---
