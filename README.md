# HR Analytics – Employee Attrition Prediction

## 📌 Objective
Use analytics to identify key factors behind employee attrition and build a machine learning model to predict which employees are likely to resign.


```

## 🧰 Tools & Technologies Used

- **Python** – Pandas, Seaborn, Scikit-learn, Matplotlib
- **Power BI** – For interactive dashboards
- **Jupyter Notebook** – For iterative development
- **Decision Tree & Logistic Regression** – Classification algorithms
- **Feature Importance** – For explainability (used instead of SHAP)

## 🔍 Key Features

- Exploratory Data Analysis (EDA) on HR metrics: department, salary band, job satisfaction, and promotion history
- Class imbalance handling using `class_weight='balanced'`
- Visual insights using Power BI (donut, bar, matrix, and line charts)
- Model interpretation using feature importance from Decision Tree

## 📊 Power BI Dashboard Includes

- Attrition by Department
- Salary Band vs Attrition
- Promotion Gap vs Attrition
- Attrition Matrix: Department × Salary Band

## 🏁 How to Run

1. Clone the repository.
2. Install the required Python packages (`requirements.txt`).
3. Open `notebooks/attrition_analysis.ipynb` and run all cells.
4. Open the Power BI file in `dashboards/` to view insights.

## 📄 Report

See `report/HR_Analytics_Attrition_Report.docx` for a 2-page summary of the project including tools, steps, and conclusions.

---

🔸 **Note**: SHAP could not be installed due to technical issues; feature importance was used as a replacement.
