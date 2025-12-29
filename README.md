# Customer Behavior Analysis Dashboard

## Project Overview

This project analyzes customer shopping behavior to uncover insights across **subscriptions, demographics, product categories, revenue, and sales performance**. The output is an interactive **Customer Behavior Dashboard** supported by SQL analysis and data cleaning workflows.

The goal is to help business stakeholders understand **who their customers are, what they buy, and which segments drive revenue**, enabling data-driven decisions in marketing, pricing, and inventory planning.

---

## Data Sources

* **customer_shopping_behavior.csv** – Raw transactional-level customer data
* **Customer_Behavior_Analysis.sql** – SQL queries for aggregation and business metrics
* **Customer Behavior Data Cleaning.ipynb** – Data cleaning, transformation, and validation

Key fields include:

* Customer demographics (Age Group, Gender)
* Product Category (Clothing, Accessories, Footwear, Outerwear)
* Subscription Status
* Purchase Amount
* Review Rating
* Shipping Type

---

## Data Cleaning & Preparation

Performed using Python (Pandas) and SQL:

* Removed duplicates and null values
* Standardized categorical fields (Gender, Subscription Status, Category)
* Validated numeric ranges for purchase amount and ratings
* Created derived fields:

  * Age Groups (Young Adult, Adult, Middle-aged, Senior)
  * Aggregated revenue and sales metrics

This ensured a clean, analysis-ready dataset.

---

## Key KPIs (Dashboard Summary)

* **Total Customers:** 3.9K
* **Average Purchase Amount:** $59.76
* **Average Review Rating:** 3.75 / 5
* **Subscription Split:**

  * Subscribed: 27%
  * Non-Subscribed: 73%

---

## Insights & Analysis

### 1. Subscription Behavior

* A majority of customers (**73%**) are **non-subscribers**
* Indicates strong potential for **subscription conversion campaigns**
* Even small increases in subscription adoption could significantly lift repeat revenue

---

### 2. Revenue by Product Category

| Category    | Revenue |
| ----------- | ------- |
| Clothing    | ~$104K  |
| Accessories | ~$74K   |
| Footwear    | ~$36K   |
| Outerwear   | ~$19K   |

**Insights:**

* Clothing is the **primary revenue driver**
* Outerwear contributes the least → potential pricing, promotion, or assortment gap

---

### 3. Sales Volume by Category

| Category    | Units Sold |
| ----------- | ---------- |
| Clothing    | 1,737      |
| Accessories | 1,240      |
| Footwear    | 599        |
| Outerwear   | 324        |

**Insights:**

* Revenue and sales volume trends align closely
* Clothing leads in both **volume and value**, making it a strategic focus area

---

### 4. Revenue by Age Group

| Age Group   | Revenue |
| ----------- | ------- |
| Young Adult | ~$62K   |
| Middle-aged | ~$59K   |
| Adult       | ~$56K   |
| Senior      | ~$56K   |

**Insights:**

* Revenue is **well distributed** across age groups
* Young Adults contribute slightly higher revenue → effective target for upsell & loyalty programs

---

### 5. Sales by Age Group

| Age Group   | Sales |
| ----------- | ----- |
| Young Adult | 1,028 |
| Middle-aged | 986   |
| Senior      | 944   |
| Adult       | 942   |

**Insights:**

* No extreme dependency on a single age segment
* Balanced customer base reduces revenue risk

---

## Business Recommendations

### Subscription Growth

* Target **non-subscribers (73%)** with:

  * First-month discounts
  * Free shipping for subscribers
  * Loyalty rewards tied to repeat purchases

### Product Strategy

* **Double down on Clothing & Accessories** (high revenue + volume)
* Re-evaluate **Outerwear**:

  * Bundle offers
  * Seasonal promotions
  * Product redesign or pricing review

### Customer Segmentation

* Focus marketing on **Young Adults & Middle-aged customers**
* Personalized recommendations based on category affinity

---

## Tools & Technologies

* **Python (Pandas, NumPy)** – Data cleaning & transformation
* **SQL** – Business logic, aggregations, KPIs
* **Power BI** – Dashboard design & visualization
* **GitHub** – Version control & portfolio presentation

---

## How to Use This Project

1. Review the cleaned dataset and SQL queries
2. Explore the dashboard for interactive insights
3. Use findings to support:

   * Marketing strategy
   * Subscription conversion
   * Product and inventory decisions

---

## Author

**Mayur Sonawane**
Aspiring Data Analyst | SQL • Power BI • Python

---

⭐ If you find this project useful, consider giving it a star on GitHub!
