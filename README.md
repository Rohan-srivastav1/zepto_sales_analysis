 comprehensive end-to-end data analysis project exploring customer behavior, delivery efficiency, and sales performance in the quick-commerce industry.

---

# 📌 Project Overview

This project presents a detailed analysis of **200,000+ sales records** from Zepto, one of India’s leading quick-commerce platforms.

Using Python’s data science ecosystem, the project uncovers:

* Customer purchasing behavior
* Delivery performance efficiency
* City-wise revenue trends
* Product category performance
* Seasonal sales fluctuations

The objective is to transform raw transactional data into **actionable business insights**.

---

# 📂 Dataset Description

The analysis is based on two structured datasets:

### 1️⃣ `zepto_sales.csv`

Contains transaction-level data:

* `order_id`
* `order_date`
* `city`
* `delivery_status`
* `delivery_time_mins`
* `total_amount`

### 2️⃣ `zepto_products.csv`

Contains product-level data:

* `product_name`
* `category`
* `base_price`

These datasets were merged and processed to generate meaningful analytical insights.

---

# 🧹 Step 1: Data Cleaning

Data preprocessing was performed to ensure accuracy and reliability.

### ✔ Handled Missing Values

* Cleaned null values in:

  * `delivery_status`
  * `city`
  * `delivery_time_mins`

### ✔ Removed Duplicate Records

* Eliminated redundant entries to maintain data integrity.

### ✔ Date Formatting

* Converted `order_date` into `datetime` format
* Enabled time-series and monthly trend analysis

---

# 🔍 Step 2: Exploratory Data Analysis (EDA)

A structured EDA approach was followed to identify patterns and trends.

---

## 📊 Sales Performance Analysis

Identified top-performing products based on total revenue.

### 🏆 Highest Grossing Products:

* Handwash
* Paneer 200g
* Toothpaste

These products significantly contributed to total revenue.

---

## 🚚 Delivery Performance Analysis

* Examined delivery time distribution
* Measured operational efficiency
* Identified performance consistency across orders

This analysis helps evaluate service quality in quick-commerce operations.

---

## 🌍 Geographic Sales Trends

Grouped and aggregated data by city to:

* Identify high-demand regions
* Compare revenue distribution
* Understand urban consumption behavior

---

# 📈 Step 3: Data Visualizations


## 🏙 Total Sales by City

A bar chart comparing revenue across cities to highlight top-performing urban markets.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c42666f-d3e2-4d4a-b51e-8792c88762cf" />


## 📅 Monthly Sales Trend

A time-series line chart showing seasonal fluctuations and revenue patterns over time.

*(Insert your GitHub image link here)*

---

## 🛍 Sales by Category

A pie chart illustrating revenue contribution of product categories such as:

* Personal Care
* Dairy & Eggs
* Household Items
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45a3edbf-a463-4b71-98f0-1bf5cfdccde5" />


## ⏱ Delivery Time Distribution

A histogram visualizing how quickly orders reach customers.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/caaa95d6-43ec-4ffe-b998-0901db2690d1" />





# 🛠 Tech Stack & Tools Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

---

# 🚀 How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/zepto-data-analysis.git
```

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3️⃣ Open the Notebook

```bash
jupyter notebook zepto_project.ipynb
```

---

# 📈 Key Insights & Business Impact

* Higher product demand directly increases revenue.
* Certain cities dominate overall sales performance.
* Delivery efficiency is consistent but can be optimized further.
* Category-level analysis reveals revenue-driving segments.

This project demonstrates how structured data analysis can support:

* Operational improvements
* Demand forecasting
* Revenue optimization
* Strategic business decisions

---

# 🎯 Conclusion

This project highlights the power of data analytics in the quick-commerce industry.

By cleaning, transforming, and visualizing large-scale transactional datasets, we can extract valuable insights into:

* Consumer behavior
* Regional demand patterns
* Delivery efficiency
* Revenue growth drivers

It serves as a strong demonstration of applied data analysis skills suitable for data analyst roles.

---

# 🔗 Connect With Me

**LinkedIn:**
https://www.linkedin.com/in/rohan-srivastav-1a623b1bb/

---

If you want next level improvement, I can:

* 🔥 Add GitHub badges (Python, Pandas, License, Stars)
* 🏆 Make it recruiter-optimized
* 📊 Add dashboard section
* 💼 Convert into resume-ready project description
* 🎨 Make it more premium & visually structured

Tell me the level you want 🚀
