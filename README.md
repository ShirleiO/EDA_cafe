# ☕ Coffee Shop Sales – Exploratory Data Analysis (EDA)

This project conducts an in-depth Exploratory Data Analysis (EDA) on a coffee shop's sales dataset. The objective is to uncover insights into sales patterns, customer behavior, and product performance to inform business decisions.

---

## 📁 Dataset Overview

The dataset comprises transactional data from a coffee shop, including:

- **Transaction ID**: Unique identifier for each transaction
- **Transaction Date**: Date of the transaction
- **Transaction Time**: Time of the transaction
- **Store ID**: Identifier for the store location
- **Store Location**: Geographical location of the store
- **Product ID**: Identifier for the product sold
- **Transaction Quantity**: Number of items sold in the transaction
- **Unit Price**: Price per unit of the product
- **Total Bill**: Total amount for the transaction
- **Product Category**: Category of the product (e.g., Beverage, Food)
- **Product Type**: Specific type within the category
- **Product Detail**: Detailed description of the product
- **Size**: Size of the product (e.g., Small, Medium, Large)
- **Month Name**: Name of the month when the transaction occurred
- **Day Name**: Name of the day when the transaction occurred
- **Hour**: Hour of the day when the transaction occurred
- **Month**: Numerical representation of the month
- **Day of Week**: Numerical representation of the day of the week

---

## 🧹 Data Cleaning and Preprocessing

- **Column Reduction**: Removed redundant columns such as `transaction_time`, `store_id`, `product_id`, `Month`, and `Day of Week` to streamline the dataset.
- **Date Formatting**: Converted `transaction_date` to datetime format and extracted the day component for further analysis.
- **Missing Values**: Verified that there are no missing values in the dataset.
- **Duplicates**: Confirmed the absence of duplicate records.

---

## 📊 Exploratory Data Analysis

### 🏪 Store Performance

- **Transaction Volume**: Analyzed the number of transactions across different store locations to identify high-performing stores.

### 🕒 Temporal Analysis

- **Hourly Sales**: Examined sales distribution across different hours of the day to determine peak business hours.
- **Daily Trends**: Investigated sales patterns across days of the week to identify the busiest days.

### 📦 Product Analysis

- **Category Performance**: Evaluated sales across different product categories to determine customer preferences.
- **Top-Selling Products**: Identified products with the highest sales volume and revenue.
- **Size Preferences**: Analyzed the popularity of different product sizes among customers.

---

## 📈 Key Insights

- **Peak Hours**: The highest sales occur during mid-morning hours, indicating a strong breakfast crowd.
- **Busiest Days**: Weekends show increased sales, suggesting higher foot traffic during these days.
- **Popular Products**: Beverages, especially coffee-based drinks, are the top-selling items.
- **Size Trends**: Medium-sized products are the most preferred among customers.

---

## 🛠️ Technologies Used

- **Python**: Programming language for data analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive computing environment.

---

## 📂 Project Structure

📁 EDA_cafe/ ├── cafe.ipynb # Jupyter notebook containing the EDA ├── data/ │ └── cafe_sales.csv # Dataset file ├── README.md # Project documentation └── requirements.txt # List of dependencies


---

## 🚀 Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ShirleiO/EDA_cafe.git
   cd EDA_cafe
   
2. Create a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install the required packages:
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   bash
   jupyter notebook

5. Open and run cafe.ipynb to explore the analysis.

---

## 📌 Future Enhancements
Interactive Dashboards: Develop dashboards using tools like Tableau or Power BI for real-time data visualization.

Predictive Modeling: Implement machine learning models to forecast sales trends.

Customer Segmentation: Analyze customer purchasing behavior for targeted marketing.











