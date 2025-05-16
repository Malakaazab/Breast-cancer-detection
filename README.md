# Breast Cancer Detection Project

This project applies machine learning techniques to detect breast cancer based on tumor characteristics from a labeled dataset.

## 🔍 Project Overview

- Used Python and data science libraries to analyze and visualize tumor data
- Trained a classification model (Logistic Regression) to differentiate between benign and malignant cases
- Created a Power BI dashboard to display key statistical insights

## 📊 Dashboard Insights

The Power BI dashboard summarizes:
- Total number of tumor cases
- Distribution of Benign vs. Malignant tumors
- Average values for tumor features (e.g., radius, perimeter)
- Top 5 largest tumors based on radius
- Tumor diagnosis per patient ID

![Dashboard Screenshot](Breast%20cancer.png)

> 📌 This dashboard was created using Power BI for visualizing breast cancer data and highlighting the most important insights.

## 📈 Model Performance

The Logistic Regression model achieved high accuracy and balanced performance metrics:

| Metric    | Class 0 (Benign) | Class 1 (Malignant) |
|-----------|------------------|---------------------|
| Precision | 0.99             | 0.98                |
| Recall    | 0.99             | 0.98                |
| F1-score  | 0.99             | 0.98                |
| Support   | 71               | 43                  |

- **Overall Accuracy:** 98.25%

## 📁 Files Included

- `Final_Project.ipynb` – The main notebook with data analysis and model building  
- `breast-cancer.csv` – The dataset used for training and analysis  
- `Breast cancer.png` – A screenshot of the Power BI dashboard  

## 🛠️ Tools Used

- Python, Pandas, NumPy, Matplotlib, scikit-learn  
- Jupyter Notebook  
- Power BI
