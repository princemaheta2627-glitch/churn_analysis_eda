# 📞 Telco Customer Churn Analysis | Exploratory Data Analysis (EDA)
---

# 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **IBM Telco Customer Churn Dataset** to identify the key factors influencing customer churn in the telecom industry.

The analysis focuses on customer demographics, contract types, billing patterns, internet services, payment methods, and tenure to uncover actionable business insights that can improve customer retention strategies.

---

# 🎯 Project Objectives

- Explore customer churn patterns
- Perform data cleaning and preprocessing
- Handle missing values and incorrect data types
- Engineer new features for better analysis
- Identify major churn drivers
- Analyze billing and contract trends
- Generate business recommendations using visualizations

---

# 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | IBM Telco Customer Churn |
| Source | Kaggle / IBM |
| Rows (Raw) | 7,043 |
| Rows (Cleaned) | 7,032 |
| Columns (Raw) | 21 |
| Columns (After Processing) | 19 |
| Churn Rate | 26.5% |
| Average Monthly Charges | $64.76 |
| Average Customer Tenure | 32.4 Months |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Repository Structure

```
Telco-Customer-Churn-EDA/
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Churn_Analysis_EDA.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── churn_distribution.png
│   ├── monthly_charges_kde.png
│   ├── total_charges_kde.png
│   ├── churn_correlation.png
│   ├── correlation_heatmap.png
│   ├── payment_method.png
│   ├── contract_analysis.png
│   └── tenure_groups.png
```

---

# 📈 Exploratory Data Analysis

The project includes:

### 🔹 Data Inspection

- Dataset Shape
- Data Types
- Descriptive Statistics
- Missing Value Detection

### 🔹 Data Cleaning

- Convert **TotalCharges** to numeric
- Handle missing values
- Remove unnecessary columns
- Remove invalid records

### 🔹 Feature Engineering

- Tenure Group Creation
- Binary Encoding of Churn
- One-Hot Encoding
- Correlation Analysis

### 🔹 Univariate Analysis

- Churn Distribution
- Contract Types
- Payment Methods
- Internet Services

### 🔹 Bivariate Analysis

- Contract vs Churn
- Payment Method vs Churn
- Partner vs Churn
- Tech Support vs Churn
- Senior Citizen vs Churn

### 🔹 Correlation Analysis

- Feature Correlation
- Heatmap
- Churn Driver Ranking

---

# 📊 Key Visualizations

- 📈 Customer Churn Distribution
- 💰 Monthly Charges KDE Plot
- 💳 Total Charges Distribution
- 📋 Contract Type Analysis
- 💵 Payment Method Comparison
- 🔥 Correlation Heatmap
- 📊 Feature Correlation with Churn
- 📅 Tenure Group Analysis

---

# 🔍 Key Insights

- 📉 Overall churn rate is **26.5%**.
- 📄 **Month-to-month contracts** show the highest churn.
- 💳 Customers using **Electronic Check** are more likely to churn.
- 💰 Higher monthly charges are associated with increased churn.
- 📅 Customers with **1–12 months tenure** have the highest churn risk.
- 🔒 Customers with **1-year and 2-year contracts** are significantly more loyal.
- 🛡️ Customers with **Tech Support** and **Online Security** churn less.
- 👤 Gender has little influence on churn behavior.
- 📞 Phone Service and Multiple Lines have minimal impact on churn.

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Converted **TotalCharges** to numeric values
- Removed invalid records
- Created tenure groups using **pd.cut()**
- Encoded the target variable using **NumPy**
- Applied **One-Hot Encoding**
- Generated a model-ready dataset

---

# 💼 Business Recommendations

- Offer discounts to month-to-month customers for annual contracts.
- Encourage customers to switch to Auto-Pay payment methods.
- Promote Tech Support and Online Security bundles.
- Focus retention efforts on customers during their first year.
- Develop targeted retention campaigns for Fiber Optic customers.

---

# 📚 Python Concepts Used

- Pandas Data Cleaning
- NumPy
- Feature Engineering
- One-Hot Encoding
- Correlation Analysis
- KDE Plots
- Heatmaps
- GroupBy Aggregation
- Countplots
- Barplots
- Custom Visualization Functions

---

# 🚀 Future Improvements

- Customer Churn Prediction using Machine Learning
- Logistic Regression
- Random Forest Classifier
- XGBoost
- SHAP Explainability
- Customer Segmentation
- Streamlit Dashboard
- Customer Lifetime Value (CLV) Analysis

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/telco-customer-churn-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install manually

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📸 Sample Output

Create an **images** folder and add screenshots from your notebook.

```
images/
├── churn_distribution.png
├── monthly_charges_kde.png
├── total_charges_kde.png
├── churn_correlation.png
├── correlation_heatmap.png
├── payment_method.png
├── contract_analysis.png
└── tenure_groups.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Scientist | Data Analyst

🔗 **GitHub:** https://github.com/princemaheta2627-glitch

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is intended for educational, portfolio, and learning purposes.
