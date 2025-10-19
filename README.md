# Churn-Customer-Analsysis
My First Project
# 📊 Customer Churn Analysis Dashboard

## 🧾 Overview
This project analyzes **customer churn** — the rate at which customers stop doing business with a company.  
It provides insights into key performance indicators such as churn rate, average customers, ARPU (Average Revenue Per User), and the main reasons for churn.  

The dashboard was designed to help businesses identify patterns in customer loss and make data-driven decisions to improve retention.

---

## 🧠 Key Insights
- **Churn Rate:** 79%
- **Average Customers:** 31.03
- **Count of Churned Customers:** 5,262
- **Total Customers (Count of IDs):** 6,687
- **ARPU (Revenue per User):** $1,083.54

### 🔍 Churn Reasons
Top reasons customers churned:
- Competitor had better devices
- Competitor made a better offer
- Poor attitude of support personnel
- Competitor offered more data
- Unclear reasons (“Don’t know”)

### 👥 Age Group Analysis
The dashboard includes an **Age Group Analysis** showing:
- Distribution of total customers by age
- Churn rate across different age segments  

This helps identify which age groups are most at risk of leaving.

---

## 🧩 Data Source
The dataset used for this analysis:
- File: **`1_1_data_preparation.xlsx`**
- Contains customer demographic data, churn status, and service details.  

You can modify or replace this dataset with your own to customize the analysis.

---

## ⚙️ Tools & Technologies
- **Excel / Power BI** for data visualization  
- **Python (Pandas, Matplotlib, Seaborn)** for preprocessing (optional)
- **Microsoft Power Query** for data cleaning  

---

## 📁 Project Structure
```
Customer-Churn-Analysis/
│
├── data/
│   └── 1_1_data_preparation.xlsx
│
├── visuals/
│   └── churn_dashboard.png
│
├── scripts/
│   └── churn_analysis.ipynb
│
└── README.md
```

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Marouane_Achraf/customer-churn-analysis.git
   ```
2. Open the Power BI file or Jupyter Notebook.
3. Load the dataset `1_1_data_preparation.xlsx`.
4. Run the analysis or view the dashboard results.

---

## 📈 Future Improvements
- Add **predictive churn modeling** using machine learning (e.g., logistic regression, random forest).
- Integrate with a **real-time dashboard** using **Streamlit** or **Dash**.
- Include **customer retention recommendations**.

---

## 🧑‍💻 Author
**Marouane Achraf**  
Data Analyst | Microsoft Excel
