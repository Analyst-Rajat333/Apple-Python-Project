# 🍎 Apple Python Project – iPhone Sales Analysis (Flipkart India)

This project presents a detailed **data analysis of Apple iPhone sales on Flipkart India** using Python. It explores product pricing, customer reviews, ratings, discounts, and performance patterns to uncover trends and consumer behavior.

---

## 📂 Dataset Overview

- 📦 **Source File**: `apple_products.csv`
- 📊 **Total Records**: 62 iPhone product listings
- ✅ **Key Columns**:
  - Product Name, Sale Price, MRP
  - Discount Percentage
  - Number of Ratings and Reviews
  - Star Rating and RAM
  - Product URL & UPC

---

## 📈 Project Workflow

1. **📥 Data Loading & Exploration**
   - Imported data using Pandas
   - Inspected structure and basic statistics

2. **🧹 Data Cleaning**
   - Verified data types
   - Handled any missing values and ensured numeric conversions

3. **📊 Data Analysis & Visualization**
   - Answered key business questions using grouped stats, bar plots, and regression plots
   - Used Seaborn and Matplotlib for visuals

---

## 💡 Key Questions Answered

### 1. 🏆 Top 10 Highest-Rated iPhones on Flipkart
- Based on `Star Rating` and visualized using a horizontal bar plot

![top_rated_iphones](https://github.com/user-attachments/assets/2ab5dbd3-365b-4b3a-93d7-c2772e82b2ab)


### 2. ⭐ Ratings Count for the Highest-Rated iPhones
- Found that the iPhone 11 Pro Max series had the highest consistent ratings (4.7)

### 3. 💬 Which iPhone Has the Most Reviews?
- `Apple iPhone SE (White, 256 GB)` had **8,161 reviews**, the highest on Flipkart

### 4. 🔗 Correlation: Sale Price vs Number of Ratings
- **Pearson Correlation**: `-0.70`
- Insight: Higher-priced iPhones tend to get fewer ratings

![saleprice_vs_ratings](https://github.com/user-attachments/assets/7f277ac5-d5b0-4e7c-9c95-385468b7f3b2)


### 5. 📉 Correlation: Discount % vs Number of Ratings
- **Pearson Correlation**: `+0.68`
- Insight: iPhones with higher discounts attract more ratings

![discount_vs_ratings](https://github.com/user-attachments/assets/0607ffc2-d67b-4106-af3c-760447424fa6)


### 6. 💰 Most & Least Expensive iPhones (With Full Specs)
- 🟢 **Cheapest**: iPhone SE (₹29,999)
- 🔴 **Costliest**: iPhone 12 Pro (₹1,40,900)

---

## 📌 Key Charts

- 📊 `top_rated_iphones.png`
- 📉 `saleprice_vs_ratings.png`
- 📈 `discount_vs_ratings.png`

> All chart images are included in the repo and displayed using markdown.

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas**, **NumPy** – Data Manipulation
- **Seaborn**, **Matplotlib** – Visualizations
- **Scipy** – Correlation (Pearson)

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Analyst-Rajat333/Apple-Python-Project.git
