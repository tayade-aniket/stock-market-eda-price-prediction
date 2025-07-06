# 📈 Stock Market EDA & Price Movement Prediction – June 2025 Dataset

This project explores the **stock market behavior in June 2025** using data analysis and feature engineering. It also builds a predictive model to determine if a stock will **close higher than its opening price** using key financial indicators.

---

## 📌 Problem Statement

Stock prices fluctuate daily based on several market dynamics. The ability to analyze these patterns and predict stock movement can help investors and analysts make smarter decisions. This project focuses on performing **EDA (Exploratory Data Analysis)** on stock data and building a **classification model** to predict daily price direction.

---

## 🧾 Project Overview

| Category        | Details                                                  |
|----------------|----------------------------------------------------------|
| 📁 Dataset      | `stock_market_june2025.csv`                              |
| 🎯 Objective    | Understand stock trends and predict daily price direction |
| 🛠️ Tools Used   | Python, Pandas, Seaborn, Scikit-learn, Matplotlib        |
| 📊 Techniques   | EDA, GroupBy, Heatmaps, Feature Engineering, Classification |
| 🎯 Target       | `Price Up` (1 if Close > Open, else 0)                   |

---

## 📊 EDA Insights

- ✅ Financials sector has the highest average stock price and trading volume.
- ✅ Technology sector has lowest average trading volume.
- ✅ Most stocks fluctuate within **±3%**, but outliers exist with **>15% change**.
- ✅ Strong positive correlations observed between price-related columns.

---

## 🔧 Features Created

| Feature            | Description                                           |
|-------------------|-------------------------------------------------------|
| `Price Range`      | High - Low price of the day                          |
| `Volatility`       | Daily range relative to opening price                |
| `Price Change`     | Difference between closing and opening price         |
| `Price Change %`   | Daily percentage return                              |
| `Price Up`         | Target variable for classification (1 if price rose) |

---


## 👨‍💻 Author

**Aniket Tayade**  
Junior Data Scientist | Passionate about building real-world ML projects  
📧 tayadeanni@gmail.com

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
