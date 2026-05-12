# 🪔 Diwali Sales Analysis (Python)

This project analyses real Diwali sales data of **11,251 customers** using Python. It explores buyer behaviour based on gender, age, state, occupation, marital status, and product category to find key purchasing trends.

---

## 🚀 Features

- Cleaned and preprocessed raw sales data (removed null values, dropped irrelevant columns, fixed data types)
- Exploratory Data Analysis (EDA) on:
  - **Gender** — who buys more and spends more
  - **Age Group** — which age group is the biggest buyer
  - **Top 10 States** — highest orders and revenue by state
  - **Marital Status** — buying behaviour of married vs unmarried customers
  - **Occupation** — which professions spend the most
  - **Product Category** — top selling categories
  - **Top 10 Products** — most ordered product IDs
- Data visualization using **Matplotlib** and **Seaborn** (Bar charts, Count plots)

---

## 📊 Dataset Structure

| Column | Description |
|--------|-------------|
| User_ID | Unique customer identifier |
| Cust_name | Customer name |
| Product_ID | Unique product identifier |
| Gender | Male / Female |
| Age Group | Age bracket of the customer |
| Age | Exact age |
| Marital_Status | Married / Unmarried |
| State | Customer's state |
| Zone | Geographic zone |
| Occupation | Customer's profession |
| Product_Category | Category of purchased product |
| Orders | Number of orders placed |
| Amount | Total amount spent (INR) |

---

## 💻 Technologies Used

- **Python 3.x**
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — advanced charts and plots
- **Google Colab** — development environment

---

## 🔍 Key Insights

- **Females** are the majority buyers and have higher purchasing power than males
- Most buyers belong to the **26–35 age group**
- Top states by orders: **Uttar Pradesh, Maharashtra, Karnataka**
- **Married women** have the highest purchasing power
- Buyers from **IT, Healthcare, and Aviation** sectors spend the most
- Most sold categories: **Food, Clothing, and Electronics**

---

## ✅ Conclusion

> Married women aged **26–35** from **UP, Maharashtra, and Karnataka**, working in **IT, Healthcare, and Aviation**, are most likely to buy products from the **Food, Clothing, and Electronics** categories.

---

## ⚡ How to Run

1. Open the notebook in **Google Colab**
2. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Upload `Diwali Sales Data.csv` to your Google Drive
4. Run all cells in order
