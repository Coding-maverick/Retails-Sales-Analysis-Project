# 🛒 Retail Sales Analysis Project  

## 📌 Overview  
Retail businesses generate large amounts of sales data daily. Analyzing this data helps uncover insights about **customer behavior, product performance, and seasonal trends**.  

In this project, we work with a **synthetic retail dataset** of 174 sales transactions to practice **data cleaning, exploratory data analysis (EDA), and visualization** using **Pandas and Matplotlib**.  

---

## 📂 Dataset  
The dataset contains the following columns:  

- **OrderID** → Unique transaction ID  
- **CustomerID** → Unique customer identifier  
- **Gender** → Customer gender  
- **Age** → Customer age  
- **City** → Customer location  
- **OrderDate** → Date of purchase  
- **Category** → Product category (Electronics, Clothing, Groceries, etc.)  
- **Quantity** → Units purchased  
- **UnitPrice** → Price per unit  
- **Revenue** → Total transaction revenue  

---

## 🎯 Objectives  

### 🔹 1. Data Cleaning  
- Fix missing values and formatting issues  
- Convert `UnitPrice` & `Revenue` from string to numeric format  
- Standardize categorical values (e.g., capitalize `Category`)  
- Handle incorrect or noisy entries  

### 🔹 2. Exploratory Data Analysis (EDA)  
- Check dataset size and column information  
- Find **top revenue-generating product category**  
- Identify **customer with the highest total spend**  
- Determine **city contributing the most revenue**  
- Find **month with the highest sales**
  
---

## 📊 Key Insights  
- 🥦 **Groceries** generated the highest overall revenue  
- 👕 **Clothing** had the highest average unit price  
- 🧑 **Customer C399** was the top spender  
- 🏙️ **Chicago** contributed the highest revenue among cities  
- 📅 **April** recorded the highest sales  

---

## 🛠️ Tools & Libraries  
- **Python**  
- **Pandas** → Data cleaning & analysis  
