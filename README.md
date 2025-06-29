# 🏡 WFH (Work From Home) Analysis System Using Machine Learning

This project analyzes remote work trends using real-world survey data collected in 2020. It applies machine learning techniques to understand which factors influence employee work-from-home preferences and to predict those preferences based on various personal and professional attributes.

---

## 📌 Project Goals

- Load and explore remote work survey data from 2020
- Clean and preprocess the data (handle nulls, encode categories)
- Apply ML algorithms to classify employee WFH preferences
- Visualize feature trends and model performance

---

## 📁 Dataset

- File used: 2020_rws.csv, 2021_rws.csv
- link- **https://www.kaggle.com/datasets/melodyyiphoiching/remote-working-survey**

---

## ⚙️ Technologies & Libraries

- Python (Google Colab)
- Pandas, NumPy – data manipulation
- Matplotlib – visualizations
- Scikit-learn – ML models, preprocessing
- OneHotEncoder – encoding categorical features

---

## 🧪 Machine Learning Workflow

1. **Data Cleaning**
   - Checked dataset shape and missing values
   - Dropped unnecessary columns
   - Cleaned column names

2. **Preprocessing**
   - Encoded categorical variables using `OneHotEncoder`
   - Split dataset into training and testing sets

3. **Modeling**
   - Applied:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
   - Evaluated with accuracy scores and confusion matrix

4. **Output**
   - Encoded feature set
   - Prediction results
   - Accuracy comparison of models

---
