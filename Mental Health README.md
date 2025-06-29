
# 🧠 Mental Health EDA: Tech Industry Insights

## 🔍 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a real-world survey dataset focused on mental health in the **tech industry**. It investigates how workplace factors, demographics, and policies impact treatment-seeking behavior and mental well-being.

---

## 🎯 Business Objective
- Identify **gaps in mental health support** across organizations.
- Understand which **factors influence employees** to seek treatment.
- Provide actionable insights to improve **workplace wellness strategies**.

---

## 📁 Dataset
- **Source**: Mental Health in Tech Survey (public dataset)
- **Size**: ~1250 responses
- **Features**:
  - Age, Gender, Country
  - Employment type, Company size
  - Mental health treatment, family history
  - Work interference, leave policy, anonymity

---

## 📊 Key Visual Insights
- Age group **25–35** is the most represented.
- Employees with **family history** are more likely to seek treatment.
- **Remote work** and **company size** significantly impact support and openness.
- **Leave policy** clarity is strongly linked to treatment-seeking.
- A lack of **anonymity** discourages employees from seeking help.

---

## 🔢 Multivariate Analysis
Used **Logistic Regression** to analyze:
- `treatment ~ gender + age + family_history`

Findings:
- **Family history** is the strongest predictor.
- **Gender** has moderate influence.
- **Age** becomes less significant when combined with other factors.

---

## 📌 Tools Used
- Python (Pandas, NumPy)
- Seaborn & Matplotlib (for data visualization)
- Statsmodels (for logistic regression)
- Jupyter Notebook

---

## 💡 Business Impact
- Helps HR and leadership identify at-risk groups.
- Supports policy creation for better **mental health resources**.
- Encourages stigma-free environments by showing evidence-backed gaps.

---

## 📂 Folder Structure
```
Mental-Health-EDA-Tech-Industry/
│
├── Mental_Health_EDA.ipynb     # Jupyter Notebook with full analysis
├── README.md                   # Project summary and instructions
├── images/                     # All visualizations used in the notebook
└── survey.csv                  # Cleaned dataset used for EDA
```

---

## ✅ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Mental-Health-EDA-Tech-Industry.git
   ```
2. Open `Mental_Health_EDA.ipynb` in Jupyter Notebook.
3. Run the notebook cell by cell to explore the data and insights.

---

## 📌 Tags
```
#mental-health #eda #data-analysis #tech-industry #hr-analytics #python #logistic-regression
```
