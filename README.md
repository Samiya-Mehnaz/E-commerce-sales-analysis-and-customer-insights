# 🛒 E-commerce Sales Dashboard  

## 📖 Project Overview  
This project analyzes an **E-commerce transactions dataset** to uncover insights into product performance, customer behavior, and sales trends.  
The goal is to create a **data-driven sales dashboard** that highlights revenue drivers and business opportunities.  

---

## 🧾 Problem Statement  
The raw dataset from Kaggle contained missing values, duplicates, and inconsistent data types.  
The challenge was to **clean, process, and analyze** the dataset to extract meaningful insights for business decisions.  

---

Dataset Source:  
The raw dataset can be downloaded from [Kaggle – E-commerce Transactions](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

## 🔍 Data Preparation  
- Removed null values (especially `CustomerID`)  
- Dropped duplicate rows  
- Converted `InvoiceDate` to datetime format  
- Created a new column:  
  - **TotalAmount = Quantity × UnitPrice**  

Final cleaned dataset: **`ecommerce_final_cleaned.csv`**
📂 Cleaned Dataset: [Download from Google Drive](https://drive.google.com/file/d/1xhf_HRD7Pchy1gWPk43AVwrVXb1XByDk/view?usp=sharing)
---

## 📊 Analysis & Visualizations  
1. **Top 10 Products by Revenue** → Bar Chart  
2. **Monthly Revenue Trend** → Line Chart  
3. **Top 5 Countries by Revenue** → Pie Chart  

### 🔑 KPI Summary  
- **Total Revenue:** (calculated in notebook)  
- **Total Customers:** (unique customer IDs)  
- **Top Country by Revenue:** UK (dominant in dataset)  

---

## 💡 Key Insights  
- Revenue is highly concentrated in a **few best-selling products**.  
- **UK leads in sales**, with a few countries contributing significantly.  
- Clear **monthly revenue trends** highlight seasonality.  
- Many customers are **Regular buyers**, suggesting opportunities for retention strategies.  

---

## 🛠️ Tools & Technologies  
- **Python (Pandas, Matplotlib, Seaborn)** → Data cleaning & visualization  
- **Jupyter Notebook** → Exploratory analysis & dashboarding  
- **GitHub** → Version control & portfolio showcase  

---
