# Customer_Shopping Behavior_Analysis
Data Analysis project - Analyzed customer shopping behavior using Python, SQL, and Power BI on 3,900 transaction records. Performed data cleaning, segmentation, and trend analysis to identify spending patterns and improve subscription and loyalty strategies.


 📘 Overview
This project analyzes customer shopping behavior using transactional data to uncover insights about spending patterns, customer segments, product preferences, and subscription trends. The end-to-end process involves **data cleaning**, **exploratory data analysis (EDA)**, **SQL-based insights**, **Power BI visualization**, and **presentation reporting**.

The goal is to turn raw data into actionable business recommendations that support strategic decision-making.

---

📊 Dataset
- **Total Records:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Product, Category, Amount, Season, Size, Color)
  - Behavior metrics (Discount Applied, Promo Code, Review Rating, Purchase Frequency)
- **Missing Values:** 37 (handled during cleaning)

---

🧰 Tools & Technologies
| Purpose | Tool |
|----------|------|
| Data Cleaning & EDA | **Python (pandas, numpy, matplotlib, seaborn)** |
| Database Storage & Analysis | **MySQL / PostgreSQL** |
| Data Visualization | **Power BI** |
| Presentation | **Gamma App (for PPT report)** |
| Reporting | **MS Word / PDF** |

---

🪜 Project Steps

 1. **Data Loading & Preparation (Python)**
- Imported dataset using `pandas`
- Checked data structure, data types, and missing values
- Cleaned and standardized column names
- Imputed missing ratings with median values per category
- Created new features (e.g., age groups, purchase frequency)

2. **Exploratory Data Analysis (EDA)**
- Visualized spending trends by category, gender, and season
- Analyzed revenue distribution and customer segments
- Identified correlations between discount usage and total spend

3. **SQL Analysis (MySQL Server)**
- Loaded cleaned data into MySQL
- Executed queries to answer key business questions:
  - Revenue by gender and age group
  - Top-rated and top-selling products
  - Subscribers vs non-subscribers revenue comparison
  - Shipping type and discount dependency analysis
  - Customer segmentation (New, Returning, Loyal)

4. **Dashboard (Power BI)**
- Built an interactive Power BI dashboard showing:
  - Revenue trends and category performance
  - Subscription metrics and customer demographics
  - Product ratings and sales insights
  - Discount usage and shipping type comparison

5. **Report & Presentation (Gamma)**
- Summarized insights, business impact, and recommendations
- Created a visually appealing presentation using **Gamma App**

---

📈 Results & Insights
- **Subscribers** spend significantly more than non-subscribers.
- **Discount users** can still be high spenders—policy optimization needed.
- **Top-rated products** show strong correlation with repeat purchases.
- **Express shipping users** generate higher average revenue.
- **Loyal customers** contribute the majority of total sales.

---

 💡 Future Enhancements
- Automate data pipeline using Airflow
- Incorporate predictive modeling for customer churn
- Integrate real-time data for dashboard updates
