# Red-Wine
# 🍷 Red Wine Quality - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Red Wine Quality Dataset** using Python. The objective is to understand the dataset, identify patterns, visualize relationships between variables, and extract meaningful insights that can help in predicting wine quality.

---

## 📂 Dataset

- **Dataset:** Red Wine Quality Dataset
- **Source:** Kaggle
- **Total Records:** 1,599
- **Total Features:** 12

### Features Included

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 📊 Steps Performed

### 1. Data Loading
- Imported the dataset using Pandas.
- Displayed the first few rows using `head()`.

### 2. Data Inspection
- Checked dataset shape.
- Examined data types.
- Used `info()` for dataset summary.
- Generated descriptive statistics using `describe()`.

### 3. Data Cleaning
- Verified missing values.
- Checked for duplicate records.
- Prepared the dataset for analysis.

### 4. Exploratory Data Analysis (EDA)

Performed the following visualizations:

- Distribution of Wine Quality
- Histograms for numerical features
- Correlation Heatmap
- Boxplots
- Scatter Plots
- Pair Plot
- Feature Distribution Analysis

---

## 📈 Key Insights

### 🍷 Wine Quality Distribution
- The dataset is **imbalanced**.
- Most wines have quality ratings of **5 and 6**.
- Very few wines have ratings of **3** or **8**.

### 🍷 Alcohol
- Wines with **higher alcohol content** generally have higher quality ratings.
- Boxplots indicate a positive relationship between alcohol and wine quality.

### 🍷 Correlation Analysis
- Alcohol shows a positive correlation with wine quality.
- Volatile acidity has a negative relationship with wine quality.
- Density is negatively correlated with alcohol.

### 🍷 Scatter Plot Analysis
- Scatter plots were used to study the relationship between Alcohol and pH while distinguishing different quality levels.

### 🍷 Pair Plot
- Pair plots helped visualize relationships among multiple numerical features and identify trends and possible correlations.

---

## 📊 Visualizations Included

- Dataset Overview
- Dataset Information
- Descriptive Statistics
- Wine Quality Distribution
- Correlation Heatmap
- Histograms
- Alcohol Distribution
- Boxplot (Alcohol vs Quality)
- Scatter Plot (Alcohol vs pH)
- Pair Plot

---

## 📁 Project Structure

```
Red-Wine-Quality-EDA
│
├── winequality-red.csv
├── Red_Wine_EDA.ipynb
├── README.md
└── images
    ├── quality_distribution.png
    ├── heatmap.png
    ├── histogram.png
    ├── boxplot.png
    ├── scatterplot.png
    └── pairplot.png
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Relationship Analysis
- Correlation Analysis
- Python Libraries for Data Analytics

---

## 🚀 Future Improvements

- Feature Engineering
- Data Preprocessing
- Machine Learning Model Building
- Wine Quality Prediction using Classification Algorithms

---

## 👨‍💻 Author

**Gautam Anand**

MBA (Business Analytics)  
UPES Dehradun

---

## ⭐ If you found this project helpful, feel free to Star this repository!
