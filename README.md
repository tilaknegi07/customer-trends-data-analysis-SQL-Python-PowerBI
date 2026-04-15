# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900+ purchases across multiple product categories. The objective is to uncover insights into customer spending patterns, segmentation, product preferences, and subscription behavior to support data-driven business decisions.

---

## 📊 Dataset Summary

* **Total Records:** 3,900
* **Total Features:** 18
* **Key Attributes:**

  * Customer Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  * Behavioral Data: Discount Applied, Promo Code Used, Purchase Frequency, Review Rating, Shipping Type
* **Missing Values:** 37 entries in Review Rating column

---

## 🐍 Data Cleaning & Preparation (Python)

* Loaded dataset using pandas
* Performed data inspection using `.info()` and `.describe()`
* Handled missing values using median imputation (category-wise)
* Standardized column names (snake_case)
* Feature Engineering:

  * Created `age_group` for segmentation
  * Derived `purchase_frequency_days`
* Removed redundant column (`promo_code_used`)
* Loaded cleaned dataset into PostgreSQL for further analysis

---

## 🗄️ Data Analysis (SQL - PostgreSQL)

Performed business-driven analysis:

* Revenue comparison by gender
* Identified high-spending customers using discounts
* Top 5 highest-rated products
* Shipping type vs purchase behavior analysis
* Subscriber vs non-subscriber revenue comparison
* Discount-dependent product identification
* Customer segmentation (New, Returning, Loyal)
* Top 3 products per category
* Subscription likelihood of repeat buyers
* Revenue contribution by age group

---

## 📈 Dashboard (Power BI)

Developed an interactive dashboard to visualize:

* Revenue trends
* Customer segmentation
* Product performance
* Subscription insights

---

## 💡 Key Insights & Recommendations

* Promote subscription plans to increase recurring revenue
* Implement loyalty programs for repeat customers
* Optimize discount strategies to protect profit margins
* Highlight top-performing products in marketing campaigns
* Focus on high-value customer segments for targeted marketing

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* SQL (PostgreSQL)
* Power BI

---

## 🚀 Project Outcome

Delivered actionable insights that can help businesses improve customer retention, optimize pricing strategies, and enhance overall sales performance.

---

## 📬 Contact

Feel free to connect for collaboration or feedback!
