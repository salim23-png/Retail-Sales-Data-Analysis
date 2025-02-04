# 🛒 Retail Sales Data Analysis

## 📌 Project Overview
This project aims to analyze retail sales data to extract meaningful insights about customer purchasing behavior, product preferences, and seasonal sales trends. The analysis involves data preprocessing, visualization, and exploratory data analysis (EDA) using Python.

## 📂 Dataset Information
The dataset used in this project is **Retail Store Performance** from Kaggle, containing transactional data with the following columns:

- `Transaction ID` – Unique identifier for each transaction.
- `Date` – Date of transaction.
- `Customer ID` – Unique identifier for each customer.
- `Gender` – Gender of the customer.
- `Age` – Age of the customer.
- `Product Category` – Category of the purchased product.
- `Quantity` – Number of items purchased.
- `Price per Unit` – Unit price of the product.
- `Total Amount` – Total cost of the transaction.

## ⚙️ Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, Plotly, Datetime, NumPy
- **Visualization Tools:** Plotly for interactive charts

## 🔎 Data Preprocessing
### 1️⃣ Data Cleaning
- Converted `Date` column to `datetime` format.
- Checked and handled missing values (if any).
- Identified and retained outliers, considering price variations between categories.

### 2️⃣ Exploratory Data Analysis (EDA)
- Created **interactive visualizations** to analyze customer behavior and sales patterns.
- Identified monthly trends, peak sales periods, and outlier distributions.

## 📊 Key Insights
### **1️⃣ Influence of Age & Gender on Purchasing Behavior**
- Customers aged **25-40 years** were the most active buyers.
- **Men purchased electronics more**, while **women preferred beauty products.**
- Older customers tended to spend more per transaction but shopped less frequently.

### **2️⃣ Sales Trends Over Time**
- **Peak sales** occurred in **June 2023**, possibly due to promotions or seasonal factors.
- **Lowest sales** were in **February 2024**, indicating a need for better post-holiday promotions.

### **3️⃣ Most Popular Product Categories**
- **Clothing and Electronics** were the top-selling categories.
- **Beauty products had high transaction volumes but lower total sales per transaction.**

### **4️⃣ Relationship Between Age, Spending, & Product Preference**
- **Younger customers** bought more fashion & beauty products.
- **Older customers** purchased high-value electronics but in smaller quantities.

### **5️⃣ Seasonal Shopping Trends**
- **Higher sales in mid-year (June) and year-end (December).**
- **Decline in sales in early months, requiring promotional strategies.**

### **6️⃣ Buying Patterns Based on Quantity**
- Electronics were purchased in **small quantities but at high prices**.
- Clothing & Beauty had **larger purchase volumes but lower transaction values**.

### **7️⃣ Product Price Distribution & Outliers**
- Electronics showed **the widest price range**, indicating premium product sales.
- **Beauty products had the lowest price range**, making them a frequent purchase.

## 📈 Recommendations & Future Improvements
🔹 **Enhance Promotions in Early Year:** Implement aggressive marketing campaigns in **February & March** to boost sales.
🔹 **Personalized Marketing:** Target customers based on **age-based preferences** to improve engagement.
🔹 **Product Bundling:** Offer bundled deals for **Beauty & Clothing products** to increase basket size.
🔹 **Installment Plans for High-End Electronics:** Encourage more **electronics purchases** through EMI options.
🔹 **Advanced ML Models for Predictions:** Future work could involve **predictive modeling** to forecast sales trends.

## 📌 Conclusion
This project provides valuable insights into customer behavior, seasonal trends, and category preferences in the retail sector. The findings can guide businesses in optimizing inventory, marketing, and pricing strategies.

---
🚀 **Next Steps:** Integrating **Machine Learning** for demand forecasting & customer segmentation!

📩 **Feedback & Contributions are Welcome!**
