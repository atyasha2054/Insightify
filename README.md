# 📊 Marketing Campaign Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-yellow.svg) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-red.svg) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Graphs-green.svg) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Clustering-orange.svg)

## 🚀 Overview
This project performs an in-depth analysis of a **Marketing Campaign Dataset** to gain insights into customer behaviors, campaign responses, and segmentation.

---

## 📂 Dataset Processing
- Converts `Dt_Customer` to **datetime format**.
- Fills missing values in `Income` with the **median income**.
- Calculates `Age` from `Year_Birth`.

---

## 📝 Task 1: Exploratory Data Analysis (EDA)
**Steps:**
- Displays dataset information, missing values, and summary statistics.
- **Visualizations:**
  - 📈 **Income Distribution**
  - 📊 **Age Distribution**
  - 📦 **Spending Distribution (Boxplot)**
  - 🔥 **Campaign Response Countplot**
  - 📊 **Acceptance Rate per Campaign (Bar Chart)**
  - 🏆 **Correlation Heatmap of Campaign Responses**

---

## 🧩 Task 2: Customer Segmentation (K-Means Clustering)
**Steps:**
- Standardizes relevant features for segmentation.
- Applies **K-Means clustering** with `k=4`.
- Assigns customers to clusters based on spending and income.
- **Visualizations:**
  - 🔍 **Customer Segments based on Income & Wine Spending**
  - 📉 **Campaign Response Rate per Cluster**

📌 **Cluster-wise Analysis:**
- Computes the **average characteristics** per cluster.
- Identifies high-value customer groups and their engagement with campaigns.

---

## 📊 Results & Insights
- Identifies **key trends in customer spending**.
- Segments customers into **four groups** based on their spending behavior.
- Analyzes the **effectiveness of different marketing campaigns**.
- Helps in targeting high-response segments more efficiently.

---

## 🛠️ Tech Stack
- **Python** 🐍
- **Pandas** 📊
- **Matplotlib** 📈
- **Seaborn** 🎨
- **Scikit-learn** 🤖

---

## 📌 How to Use
1️⃣ Clone the repository:
```bash
$ git clone https://github.com/your-repo/marketing-analysis.git
$ cd marketing-analysis
```
2️⃣ Install dependencies:
```bash
$ pip install pandas matplotlib seaborn scikit-learn
```
3️⃣ Run the script:
```bash
$ python analysis.py
```

---

## 🎯 Future Enhancements
✅ Implement additional **clustering techniques** (Hierarchical, DBSCAN).  
✅ Build an **interactive dashboard** using **Power BI / Tableau**.  
✅ Develop a **predictive model** for campaign success.

---

🚀 **Contributions are welcome!** Feel free to fork, improve, and submit PRs. 😊

