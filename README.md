# Liver Disease Prediction: A Comparative Study of Classification Models

## 📌 Project Overview
This project focuses on predicting liver disease using clinical biochemical markers from the **Indian Liver Patient Dataset (ILPD)**. We developed a machine learning framework to compare three classification models: **Logistic Regression, Decision Trees, and Random Forests**, aiming to optimize diagnostic accuracy and minimize missed cases (**False Negatives**).

## 🚀 Key Highlights
* **High Clinical Sensitivity:** Achieved a **Recall of 97.59%** using a tuned Logistic Regression model, which is critical for early medical screening.
* **Advanced Data Cleaning:** Implemented **IQR-based Winsorization** to handle extreme outliers in liver enzymes (ALT, AST) without losing significant clinical data.
* **Optimization:** Conducted systematic hyperparameter tuning using **GridSearchCV** to find the best model configurations.

## 🛠️ Technical Methodology
1. **Exploratory Data Analysis (EDA):** Statistical evaluation (Skewness, Kurtosis) and Normality testing (**Shapiro-Wilk**).
2. **Data Preprocessing:** 
   - Handled missing values using **Median Imputation**.
   - Binary encoding for categorical features (Gender).
   - Feature Scaling using **StandardScaler** to improve model convergence.
3. **Outlier Treatment:** Applied Winsorization to stabilize variance in highly skewed features (e.g., Total Bilirubin, Enzymes) [Page 33 of report].
4. **Performance Evaluation:** Models were compared based on Accuracy, Precision, Recall, F1-Score, and AUC-ROC curves.

## 📊 Final Performance (Tuned Logistic Regression)

| Metric | Result |
| :--- | :--- |
| **Recall** | **97.59%** |
| **Accuracy** | **76.92%** |
| **F1-Score** | **0.857** |
| **AUC-ROC** | **85.61%** |

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Seaborn.

## 🎓 Project Context
This project was developed as part of a group assignment (Group 3) for the **CIS 517 - Data Mining & Data Warehousing** course at **Imam Abdulrahman Bin Faisal University (IAU)**.

---
*For a detailed breakdown of the statistical analysis and model tuning, please refer to the full PDF report in the repository.*
