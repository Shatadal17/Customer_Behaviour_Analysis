# 🛍️ Customer Behavior Analysis – End-to-End Data Analytics Project

### 🎯 **Project Objective**

The goal of this project was to analyze **customer shopping behavior** to identify key business insights — such as spending patterns, customer segmentation, popular products, and the impact of discounts or subscriptions — using **Python, MySQL, and Power BI**.

This project helped me understand the **end-to-end process of solving a real-world business problem through data** — from raw data exploration to visualization and insight generation.

---

## 🧩 **Project Workflow**

### 1️⃣ **Exploratory Data Analysis (EDA) – Python**

**Tools Used:** `pandas`, `numpy`, `matplotlib`, `seaborn`

**Steps Performed:**
- **Data Loading & Inspection:** Loaded the dataset into a pandas DataFrame and checked for missing values, datatypes, and duplicates.  
- **Data Cleaning:** Handled missing data, corrected data types, and standardized categorical values (e.g., gender, shipping type, discount applied).  
- **Feature Engineering:**  
  - Created new columns such as **Age Group** and **Revenue per Purchase**.  
  - Derived useful categories like **Customer Segment** based on previous purchases.  
- **Exploratory Analysis:**  
  - Visualized spending patterns across **age groups, gender, and subscription status**.  
  - Analyzed the effect of **discounts, shipping types, and reviews** on purchase amounts.  
  - Identified **top-selling products and categories** using bar plots and histograms.  

**Key Insights:**
- Female customers tended to spend slightly more on average.  
- Loyal customers (with multiple past purchases) contributed most to revenue.  
- Products with discounts still generated significant sales volume.  

---

### 2️⃣ **Business Problem Solving – MySQL**

**Tool Used:** MySQL Workbench  
**Database:** `customer_behavior` (Created from cleaned CSV)

Using SQL queries, I solved **10 business problems** such as:

| **Business Question** | **SQL Insight** |
|------------------------|----------------|
| 1. What is the total revenue by gender? | Compared total revenue of male vs female customers. |
| 2. Who used discounts but spent above average? | Identified high-value discount users. |
| 3. Which are the top 5 products by average rating? | Found best-rated items based on reviews. |
| 4. Compare average purchase amount by shipping type. | Compared Standard vs Express shipping users. |
| 5. Do subscribed customers spend more? | Analyzed revenue and average spend for subscribers vs non-subscribers. |
| 6. Which products have the highest discount usage? | Found top 5 discounted products. |
| 7. Segment customers (New, Returning, Loyal). | Categorized customers based on previous purchases. |
| 8. Top 3 most purchased items in each category. | Used window functions (ROW_NUMBER) to find category leaders. |
| 9. Are repeat buyers likely to subscribe? | Checked correlation between repeat purchases and subscription. |
| 10. Revenue contribution by age group. | Identified most profitable customer age groups. |

These SQL queries provided **structured business insights** that connected the exploratory analysis to measurable outcomes.

---

### 3️⃣ **Visualization & Dashboard – Power BI**

**Tool Used:** Microsoft Power BI  
**Connection:** Directly connected to MySQL database

**Dashboard Highlights:**
- Interactive visuals showing:  
  - **Revenue by Gender and Age Group**  
  - **Top Products and Categories**  
  - **Customer Segmentation (New, Returning, Loyal)**  
  - **Impact of Subscription & Discounts**  
  - **Average Spend by Shipping Type**  
- Used **slicers and filters** for dynamic exploration.  
- Designed **KPIs** like total revenue, average purchase value, and customer count.

**Outcome:**  
The dashboard provides a **comprehensive and interactive overview** of customer trends that help businesses make better marketing and product decisions.

---

## 📈 **Key Learnings**

- Understood the **complete data analysis lifecycle**: from cleaning and feature engineering to SQL-based querying and visualization.  
- Learned how to structure SQL queries to derive **actionable business insights**.  
- Improved skills in connecting databases to **Power BI** for dynamic dashboards.  
- Gained clarity on how **data analytics supports business decision-making**.  

---

## 🧠 **Tools & Technologies**

| Category | Tools Used |
|-----------|-------------|
| Programming | Python (`pandas`, `numpy`, `matplotlib`, `seaborn`) |
| Database | MySQL |
| Visualization | Power BI |
| Concepts | EDA, Feature Engineering, SQL Joins, Aggregations, Window Functions, Dashboarding |

---

## 🏁 **Project Summary**

This project demonstrates how to perform **end-to-end customer behavior analysis** — transforming raw data into strategic insights.  
Through this project, I learned not just the technical aspects of Python, SQL, and Power BI, but also how to **think like a data analyst solving real business problems**.

---

## 💡 **Acknowledgment**

This project was inspired by the amazing YouTube channel **[Amlan Mohanty](https://www.youtube.com/@AmlanMohanty)**, whose tutorials helped me understand the step-by-step approach to solving business problems using data analytics.

---

## 🚀 **Next Steps**

I plan to continue building similar **end-to-end projects** and share them on my **GitHub** and **LinkedIn** to inspire other learners.  
Each project will focus on real-world business cases and showcase how data analytics can create real impact.

---

