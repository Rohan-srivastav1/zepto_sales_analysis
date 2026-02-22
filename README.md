Zepto Sales Data Analysis Project 🛒📊
Project Overview
This project provides a comprehensive analysis of over 200,000 sales records from Zepto, a leading quick-commerce platform. Using Python's data science ecosystem, the project explores customer behavior, delivery efficiency, and sales performance across different cities and product categories.

📂 Dataset Description
The analysis is based on two primary datasets:


zepto_sales.csv: Contains transaction details including order_id, order_date, city, delivery_status, and total_amount.


zepto_products.csv: Contains product-level information like product_name, category, and base_price.

🔍 Key Analysis & Findings
The project follows a structured data science workflow:

1. Data Cleaning
Handled missing values in delivery_status, city, and delivery_time_mins.

Removed duplicate records to ensure data integrity.

Converted date columns to datetime objects for time-series analysis.

2. Exploratory Data Analysis (EDA)
Sales Performance: Identified top-performing products. The highest-grossing products include Handwash, Paneer 200g, and Toothpaste.
+1


Delivery Metrics: Analyzed the distribution of delivery times to measure platform efficiency.


Geographic Trends: Grouped sales by city to identify high-demand regions.

3. Visualizations
The project includes several key plots to communicate findings:


Total Sales by City: A bar chart comparing revenue across different urban centers.


Monthly Sales Trend: A line chart showing seasonal fluctuations in sales.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6e898ba2-08c3-4afc-ba30-a33001e37bcf" />



Sales by Category: A pie chart illustrating the revenue contribution of different product categories (e.g., Personal Care, Dairy & Eggs).

+1


Delivery Time Distribution: A histogram visualizing how quickly orders reach customers.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/85240ed7-b149-4f75-8ce6-64e8fbf9e655" />


LINKED IN =https://www.linkedin.com/in/rohan-srivastav-1a623b1bb/
MY RESUME=https://drive.google.com/drive/u/0/my-drive


🚀 How to Run
Clone this repository:

Bash
git clone https://github.com/your-username/zepto-data-analysis.git
Install the required libraries:

Bash
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook:

Bash
jupyter notebook zepto_project.ipynb

📈 Conclusion

This project demonstrates the power of data analysis in the quick-commerce industry. By cleaning and visualizing large-scale datasets, we can derive actionable insights into consumer preferences and operational efficiency.

