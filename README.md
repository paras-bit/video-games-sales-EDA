## 🎮 Video Game Sales — Exploratory Data Analysis

### 📊 Project Overview
This project explores the **Video Game Sales dataset** from Kaggle, which contains information about over **16,000 video games** released across various platforms, genres, and regions.  
The goal of this analysis is to uncover **trends, patterns, and insights** in the global gaming industry using Exploratory Data Analysis (EDA).

---

## 🔍 Data Analysis Summary

### 1️⃣ Data Overview
- Total Records: **16,500+**
- Attributes: **11**
- Key Features: `Name`, `Platform`, `Year`, `Genre`, `Publisher`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`
- Covers games released between **1980 and 2020**

### 2️⃣ Data Cleaning
- Handled **missing values** in `Year` and `Publisher`
- Removed **duplicate records**
- Standardized text formatting for `Genre` and `Platform`
- Treated **outliers** in `Global_Sales` using the IQR method

### 3️⃣ Descriptive Statistics
- **Mean Global Sales:** ~0.54 million units  
- **Median Global Sales:** ~0.17 million units  
- **Right-skewed distribution** — only a few titles achieve massive global sales  
- **NA_Sales** shows the highest average regional sales

---

## 📈 Key Insights

### 🎮 Platform Insights
- **PS2**, **X360**, and **Wii** are the most successful platforms in terms of total sales.
- Game releases and sales peaked during **2005–2010**, the golden era of console gaming.

### 🎭 Genre Insights
- **Action** and **Sports** are the most popular genres globally.
- **Shooter** games, though fewer in number, achieve high sales per title.
- **Role-Playing** games perform exceptionally well in **Japan**.

### 🌍 Regional Insights
- **North America** leads in global sales contribution, followed by **Europe** and **Japan**.
- Regional preferences differ — for example, **Japan** prefers RPGs, while **NA** favors Action and Shooter genres.

### 💰 Sales Insights
- Sales are **highly right-skewed** — a few blockbuster games dominate total revenue.
- Most games sell fewer than **1 million copies**, confirming a **hit-driven market** structure.

---

## 🧠 Conclusion
The video game industry is dominated by a small number of best-selling titles, with regional preferences strongly shaping global sales trends.  
**Action**, **Sports**, and **Shooter** genres consistently outperform others, and the **2005–2010 period** stands out as the golden age of gaming.  
This dataset provides valuable insights for **publishers, analysts, and marketers** to understand market demand and platform success.

---

## 🛠️ Tools Used
- **Python** (pandas, numpy, matplotlib, seaborn, sklearn)
- **Jupyter Notebook**
- **Git & GitHub**

---

*Author: [Paras](https://github.com/paras-bit)*  
*Dataset: [Video Game Sales - Kaggle](https://www.kaggle.com/gregorut/videogamesales)*
