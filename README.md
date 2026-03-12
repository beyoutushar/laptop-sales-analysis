# 💻 Laptop Sales — Python Data Analytics Project

A complete data analytics project analyzing **10,000 laptop sales records** using Python, Pandas, Matplotlib, and Seaborn.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `laptop_sales_analysis_FINAL.ipynb` | Main Jupyter Notebook with all tasks |
| `laptop_sales.csv` | Dataset with 10,000 sales records |

---

## 📊 Dataset Overview

| Column | Description |
|--------|-------------|
| Order_ID | Unique order number |
| Date | Date of sale |
| Brand | Laptop brand (Asus, Dell, HP, etc.) |
| Model_Name | Laptop model |
| Laptop_Type | Category (Gaming, Student, Business, etc.) |
| City | City of sale |
| State | State of sale |
| Quantity | Number of units sold |
| Unit_Price | Selling price per unit |
| Unit_Cost | Cost price per unit |
| Revenue | Total revenue per order |
| Profit | Total profit per order |

---

## ✅ Part 1 — Data Manipulation Tasks (10 Tasks)

| # | Task | Method |
|---|------|--------|
| 1 | Total Revenue KPI | .sum() |
| 2 | Total Profit KPI | .sum() |
| 3 | Total Quantity Sold | .sum() |
| 4 | Average Unit Price | .mean() |
| 5 | Top 5 Brands by Revenue | .groupby() + .sort_values() |
| 6 | Most Sold Laptop Type | .groupby() + .sort_values() |
| 7 | City with Highest Sales | .groupby() + .head(1) |
| 8 | State with Highest Profit | .groupby() + .head(1) |
| 9 | Monthly Revenue Trend | pd.to_datetime() + .dt.to_period() |
| 10 | Profit Margin Calculation | New column + .mean() |

---

## 🎨 Part 2 — Visualization Tasks (10 Tasks)

| # | Chart | Library |
|---|-------|---------|
| 1 | Bar Chart — Revenue by Brand | Seaborn |
| 2 | Pie Chart — Laptop Type Distribution | Matplotlib |
| 3 | Bar Chart — Top 10 Cities by Revenue | Seaborn |
| 4 | Line Chart — Monthly Revenue Trend | Matplotlib |
| 5 | Bar Chart — Profit by Brand | Seaborn |
| 6 | Scatter Plot — Unit Price vs Profit | Seaborn |
| 7 | Histogram — Distribution of Unit Price | Seaborn |
| 8 | Box Plot — Revenue by Laptop Type | Seaborn |
| 9 | Heatmap — Correlation Matrix | Seaborn |
| 10 | Bar Chart — Top 10 Models by Quantity | Seaborn |

---

## 🔑 Key Results

| KPI | Value |
|-----|-------|
| Total Revenue | ₹3,294,683,565 |
| Total Profit | ₹819,395,366 |
| Total Quantity Sold | 29,930 units |
| Average Unit Price | ₹1,10,088.55 |
| Average Profit Margin | 24.92% |
| Top Brand by Revenue | Asus |
| Top City by Revenue | Bengaluru |
| Top State by Profit | Gujarat |
| Most Sold Laptop Type | 2-in-1 |

---

## 🛠️ Libraries Used

pip install pandas matplotlib seaborn

---

## ▶️ How to Run

1. Clone this repository
2. Place laptop_sales.csv in the project folder
3. Open laptop_sales_analysis_FINAL.ipynb in Jupyter Notebook
4. Click Kernel → Restart & Run All

---

## 👤 Author

Tushar Bokefod
- GitHub: @beyoutushar
- LinkedIn: https://www.linkedin.com/in/tushar-the-electronics-engineer
