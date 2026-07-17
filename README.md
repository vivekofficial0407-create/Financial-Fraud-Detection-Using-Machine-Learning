# Financial Fraud Detection Using Machine Learning

## Project Overview

Financial fraud has become one of the major challenges faced by banks and online payment systems. Detecting fraudulent transactions manually is difficult because of the large number of daily transactions. This project develops a Machine Learning-based Financial Fraud Detection System that classifies transactions as **Genuine** or **Fraudulent** using different classification algorithms.

The project includes complete data preprocessing, exploratory data analysis (EDA), outlier detection, feature scaling, model training, model evaluation, and comparison of multiple machine learning models.

---

## Objective

The objective of this project is to build an intelligent fraud detection system that can accurately identify fraudulent financial transactions using Machine Learning techniques.

---

## Dataset

* Dataset Name: Credit Card Fraud Detection Dataset
* Total Records: 93,181+
* File Format: CSV
* Target Variable: Class

  * 0 → Genuine Transaction
  * 1 → Fraudulent Transaction

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Data Inspection
* Missing Value Detection
* Duplicate Record Removal
* Histogram
* Boxplot
* Correlation Heatmap
* Bar Plot
* Outlier Detection using IQR Method

---

## Machine Learning Models Used

### Logistic Regression

A linear classification algorithm used as the baseline model for fraud detection.

### Decision Tree

A tree-based supervised learning algorithm used for classification.

### Random Forest

An ensemble learning algorithm that combines multiple Decision Trees to improve prediction accuracy and reduce overfitting.

---

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 99.89%   |
| Decision Tree       | 99.92%   |
| Random Forest       | 99.96%   |

Random Forest achieved the highest overall performance and was selected as the final model for fraud detection.

---

## Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Understand Dataset
4. Handle Missing Values
5. Remove Duplicate Records
6. Perform Exploratory Data Analysis
7. Detect Outliers using IQR
8. Select Features and Target Variable
9. Split Dataset into Training and Testing Sets
10. Standardize Features using StandardScaler
11. Train Logistic Regression Model
12. Train Decision Tree Model
13. Train Random Forest Model
14. Compare Model Performance
15. Draw Accuracy Comparison Graph
16. Conclude the Best Performing Model

---

## Project Structure

```
Financial-Fraud-Detection-Using-Machine-Learning/

│

├── Dataset/
│     └── creditcard.csv
│
├── Images/
│     ├── histogram.png
│     ├── boxplot.png
│     ├── heatmap.png
│     └── accuracy_graph.png
│
├── Financial_Fraud_Detection_Using_Machine_Learning.ipynb
│
├── README.md
│
├── requirements.txt
│
└── LICENSE
```
---

## Conclusion

This project successfully demonstrates how Machine Learning can be applied to identify fraudulent financial transactions. Three classification algorithms were implemented and evaluated. Among them, **Random Forest** achieved the highest accuracy and overall performance, making it the most suitable model for this dataset.

---

## Author

**Vivek Gautam**

B.Tech CSE (Data Science)

GitHub: https://github.com/vivekofficial0407-create

LinkedIn: https://www.linkedin.com/in/vivek-gautam-a4b478323
