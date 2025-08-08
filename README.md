# 🩺 Diabetes Data Analysis

## 📖 Project Overview
This project presents an **exploratory data analysis (EDA)** of the **Pima Indians Diabetes Dataset** to identify medical indicators that are most correlated with diabetes.  
The analysis leverages **Python’s data science ecosystem** to clean, visualize, and interpret the dataset in order to uncover meaningful patterns.

---

## 📂 Dataset Information
**Source:** Pima Indians Diabetes Database (UCI Machine Learning Repository / Kaggle)  
**Total Records:** 768  
**Features:**
- **Pregnancies** – Number of times pregnant
- **Glucose** – Plasma glucose concentration (mg/dL)
- **BloodPressure** – Diastolic blood pressure (mm Hg)
- **SkinThickness** – Triceps skin fold thickness (mm)
- **Insulin** – 2-Hour serum insulin (mu U/ml)
- **BMI** – Body Mass Index
- **DiabetesPedigreeFunction** – Diabetes family history function score
- **Age** – Age in years
- **Outcome** – Target variable (0 = No Diabetes, 1 = Diabetes)

---

## 📊 Analysis Workflow
1. **Data Cleaning & Preparation**
   - Checked for missing and zero values.
   - Identified unrealistic values in features such as `Glucose`, `BloodPressure`, and `BMI`.
   
2. **Univariate Analysis**
   - Distribution plots and histograms for each feature.
   
3. **Bivariate Analysis**
   - Boxplots comparing each feature with the `Outcome`.
   
4. **Correlation Analysis**
   - Heatmap to visualize inter-feature relationships.
   
5. **Outcome Distribution**
   - Class distribution analysis to assess dataset imbalance.

---

## 📌 Key Findings
- **Glucose**, **BMI**, **Age**, and **Pregnancies** show the strongest correlation with diabetes occurrence.
- The dataset is **moderately imbalanced** (~65% non-diabetic, ~35% diabetic).
- Several features contain zeros where physiologically impossible, suggesting missing data.
- High glucose and BMI levels significantly increase diabetes probability.

---

## 🛠️ Tools & Technologies
- **Python 3.x**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis

---

## 🚀 How to Run This Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/BhaviK1247/diabetes-data-analysis.git
