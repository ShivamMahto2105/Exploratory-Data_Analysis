# 🪔 Diwali Sales Analysis – EDA Project

This project presents a detailed exploratory data analysis of a retail sales dataset based on Diwali shopping in India. The goal is to uncover purchasing patterns across demographics, geography, and product categories to support business strategy and customer targeting.

---

## 🧠 Objective

To analyze customer behavior during Diwali and identify:

- 👨‍👩‍👧‍👦 Key demographics (age, gender, marital status) of top spenders  
- 🌍 High-performing states and occupations by total sales  
- 🛍️ Top-selling product categories and sub-categories  
- 📈 Actionable insights for marketing and inventory optimization  

---

## 📊 Dataset Overview

The dataset includes retail transactions collected during the Diwali festival season with the following key columns:

| Column Name      | Description                                 |
|------------------|---------------------------------------------|
| `User_ID`        | Unique customer identifier                  |
| `Gender`         | Gender of the buyer                         |
| `Age`            | Age group of the buyer                      |
| `Marital_Status` | 0 = Single, 1 = Married                     |
| `Occupation`     | Type of profession (coded)                 |
| `City_Category`  | A, B, C – Tier of city                      |
| `Stay_In_Current_City_Years` | Duration in current city       |
| `Product_Category_1` | Main product category                   |
| `Product_Category_2/3` | Additional product categories         |
| `Purchase`       | Purchase amount in INR                      |

📄 [**Click here to view the dataset**](https://github.com/Shivam-DataAnalytics/EDA-Projects/blob/main/Diwali_Sales_Analysis/Diwali Sales Data.csv)  
📘 [**Click here to view the EDA Notebook**](https://github.com/Shivam-DataAnalytics/EDA-Projects/blob/main/Diwali_Sales_Analysis/Diwali_Sales_EDA.ipynb)

---

## 🧪 Key Findings

- ✅ **Married women (age 26–35)** were the top spenders during Diwali  
- ✅ Buyers from **Uttar Pradesh, Maharashtra, and Karnataka** led in purchases  
- ✅ Most buyers worked in **IT, Healthcare, and Aviation** sectors  
- ✅ **Food, clothing, and electronics** were the highest selling categories  
- ✅ **Tier 2 cities** contributed significantly to total revenue

📌 These insights help businesses personalize offers, stock the right inventory, and target campaigns effectively.

---

## 🛠️ Tools & Techniques Used

- **Python (Jupyter Notebook)** – Main environment for analysis  
- **Pandas** – Data cleaning, grouping, filtering  
- **NumPy** – Numerical operations  
- **Matplotlib** – Line/bar charts and plots  
- **Seaborn** – Heatmaps, countplots, boxplots for rich visualization  
- **VS Code** – Used for script organization and version control  

---

## 📈 Sample Visualizations

📍 [Amount Vs Product_Category](https://github.com/Shivam-DataAnalytics/EDA-Projects/blob/main/Diwali_Sales_Analysis/visuals/gender_vs_purchase.png)  
📍 [Product_Id Vs Order](https://github.com/Shivam-DataAnalytics/EDA-Projects/blob/main/Diwali_Sales_Analysis/visuals/state_vs_sales.png)  
📍 [Total Amount By State](https://github.com/Shivam-DataAnalytics/EDA-Projects/blob/main/Diwali_Sales_Analysis/visuals/occupation_vs_sales.png)


## 📌 Conclusion

This project demonstrates the power of EDA in retail analytics. By uncovering meaningful patterns in customer purchases during Diwali, businesses can make data-driven decisions to improve engagement, marketing ROI, and inventory management.

