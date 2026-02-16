# 📊 Student Performance Analysis (EDA) using Python

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a student performance dataset to analyze factors affecting students' academic results. The dataset contains demographic, social, and academic-related features used to identify patterns and relationships influencing final grades.

The analysis focuses on understanding how study habits, family background, lifestyle, and school-related factors impact student performance.

---

## 🎯 Objectives

- Understand dataset structure and feature distribution
- Analyze factors affecting student academic performance
- Explore relationships between lifestyle and grades
- Identify important features influencing final score (G3)
- Generate data-driven insights using visualization

---

## 📂 Dataset Description

The dataset contains **395 student records** with **33 features** including:

### 👨‍🎓 Student Information

- school — School name (GP/MS)
- sex — Gender
- age — Student age
- address — Urban/Rural
- famsize — Family size
- Pstatus — Parent cohabitation status

### 👨‍👩‍👧 Family & Background

- Medu — Mother's education
- Fedu — Father's education
- Mjob — Mother's job
- Fjob — Father's job
- guardian — Student guardian

### 📚 Academic Factors

- studytime — Weekly study time
- failures — Number of past class failures
- schoolsup — Extra educational support
- paid — Extra paid classes
- higher — Higher education intention

### 🧠 Lifestyle & Social Factors

- activities — Extracurricular activities
- internet — Internet access
- romantic — Romantic relationship
- freetime — Free time after school
- goout — Going out with friends
- Dalc — Workday alcohol consumption
- Walc — Weekend alcohol consumption
- health — Current health status
- absences — Number of school absences

### 📊 Grades

- G1 — First period grade
- G2 — Second period grade
- G3 — Final grade (Target variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis Steps

### ✅ Data Understanding

- Dataset shape and columns overview
- Data type inspection
- Statistical summary

### ✅ Data Cleaning

- Missing value check
- Duplicate records handling
- Data consistency validation

### ✅ Univariate Analysis

- Distribution of grades (G1, G2, G3)
- Age and studytime distribution
- Lifestyle variable analysis

### ✅ Bivariate Analysis

- Studytime vs Final Grade
- Absences vs Performance
- Parental education vs Grades
- Gender-based comparison

### ✅ Visualization

- Correlation heatmap
- Boxplots for performance comparison
- Histograms for score distribution
- Countplots for categorical features

---

## 📈 Key Insights

- Study time shows positive correlation with performance.
- Higher number of failures negatively impacts grades.
- Absences may affect final performance.
- Parental education level influences academic outcomes.

*(Update this section with your actual findings after analysis)*

---

## 🗂️ Project Structure

```
student-performance-analysis/
│
├── data/
│   └── student_data.csv
│
├── notebooks/
│   └── student_performance_EDA.ipynb
│
├── images/
│   └── plots.png
│
├── requirements.txt
│
└── README.md
```

## 🚀 Future Improvements

- Build machine learning model for grade prediction
- Feature engineering
- Dashboard visualization (Streamlit/Power BI)
- Automated EDA report generation

