# Jamboree Education – Graduate Admission Prediction Using Linear Regression

This project aims to predict a student's chances of admission to top universities based on academic credentials and application strength using linear regression techniques. The analysis supports Jamboree's feature that helps Indian applicants estimate their Ivy League admission probabilities.

---

## 📊 Problem Statement

Jamboree wants to identify which academic factors (GRE, TOEFL, SOP, GPA, etc.) most influence a student's chance of graduate admission. This helps guide students toward stronger applications and improves personalized feedback on their platform.

---

## 📁 Dataset Overview

The dataset contains:
- `GRE Score` (out of 340)
- `TOEFL Score` (out of 120)
- `University Rating` (1 to 5)
- `SOP`, `LOR` Strength (1 to 5)
- `CGPA` (out of 10)
- `Research` Experience (0 or 1)
- `Chance of Admit` (target variable)

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Scikit-learn

---

## 📈 Project Workflow

1. **EDA** – Distribution plots, summary stats, and outlier analysis
2. **Correlation Analysis** – Heatmaps and pair plots to understand variable relationships
3. **Feature Engineering** – Dropped unnecessary features (like Serial No.)
4. **Model Building** – Linear Regression with Statsmodels and Scikit-learn
5. **Assumption Testing**:
   - Multicollinearity (VIF)
   - Linearity of residuals
   - Homoscedasticity
   - Normality of residuals (QQ plot, histogram)
   - Mean of residuals ≈ 0
6. **Model Evaluation**:
   - MAE, RMSE
   - R² and Adjusted R²
   - Ridge and Lasso Regression comparisons

---

## 📌 Key Insights

- **GRE Score**, **TOEFL Score**, **CGPA**, and **Research** are strong predictors.
- VIF helped identify and address multicollinearity.
- All linear regression assumptions were tested and validated.
- Ridge and Lasso gave similar performance, with minimal need for regularization.

---

## 📂 Files in this Repository

- `Jamboree_Admission_Linear_Regression.ipynb` – Main notebook
- `jamboree_admission.csv` – Dataset
- `README.md` – Project documentation
- (Optional) PDF/HTML summary

---

## 💡 Business Recommendations

- Encourage students with research experience and higher GPAs to apply more confidently.
- Provide targeted study plans to improve GRE/TOEFL scores.
- Build a front-end estimator tool using this model to help students gauge admission chances live.

---

## 🤝 Connect

Feel free to raise issues, give feedback, or connect on [LinkedIn](https://www.linkedin.com/in/varshil-gandhi-08470b200/).

