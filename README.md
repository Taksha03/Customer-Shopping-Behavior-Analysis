# 📊 Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using Python, SQL, and Power BI. The objective is to identify purchasing patterns, understand customer segments, and evaluate the impact of marketing strategies such as discounts and subscriptions.

The project demonstrates a complete end-to-end data analytics workflow, including data cleaning, exploratory analysis, SQL querying, and dashboard visualization.

---

## 📂 Dataset
The dataset contains detailed information about customer transactions and behavior.

**Key columns include:**

- Customer Information: customer_id, age, gender, location  
- Product Details: item_purchased, category, size, color, season  
- Transaction Data: purchase_amount, payment_method, shipping_type  
- Customer Behavior: review_rating, previous_purchases, frequency_of_purchases  
- Marketing Factors: discount_applied, promo_code_used, subscription_status  

Format: CSV file

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- SQL (PostgreSQL / MySQL / SQL Server)  
- Power BI  

---

## 🔄 Project Workflow

### 1. Data Loading & Cleaning (Python)
- Loaded dataset using Pandas  
- Checked for missing values and duplicates  
- Standardized categorical values  
- Converted columns into appropriate data types  

---

### 2. Exploratory Data Analysis (Python)
- Analyzed customer demographics (age, gender)  
- Studied purchasing behavior across categories and seasons  
- Examined relationships between purchase amount, frequency, and previous purchases  
- Visualized trends using charts and distributions  

---

### 3. SQL Analysis
- Imported cleaned data into a relational database  
- Performed queries for:
  - Total revenue  
  - Category-wise sales and revenue  
  - Customer segmentation  
  - Impact of discounts and subscriptions  
  - Age-group analysis  

---

### 4. Power BI Dashboard
- Total customers: 2.77K  
- Average purchase amount: $59.51  
- Average review rating: 3.75  
- Revenue by category  
- Sales by category  
- Customer segmentation (age group, gender)  
- Subscription impact  

---

## 📊 Key Insights

- Clothing is the top-performing category in both sales and revenue  
- Young adults and middle-aged customers contribute the highest revenue  
- Customers with more previous purchases tend to spend more  
- Discounts and promo codes increase purchase likelihood  
- Subscription users show higher engagement and repeat purchases  
- Average rating of 3.75 indicates good satisfaction with room for improvement  

---

## ▶️ How to Run the Project

### 1. Clone the repository
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git  
cd customer-shopping-behavior-analysis  

### 2. Install required libraries
pip install pandas numpy matplotlib seaborn  

### 3. Run Python analysis
- Open notebook or script  
- Run all cells  

### 4. Run SQL queries
- Import dataset into database  
- Execute SQL file  

### 5. Open Power BI dashboard
- Open .pbix file in Power BI Desktop  
- Refresh data if needed  

---

## 📁 Project Structure
data/  
sql/  
dashboard/  
notebooks/  
README.md  

---

## 🚀 Conclusion
This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI. It highlights skills in data cleaning, analysis, visualization, and business insight generation.
