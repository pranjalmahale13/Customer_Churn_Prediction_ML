# Customer Churn Prediction using Machine Learning

This project focuses on predicting whether a **bank customer is likely to churn (leave the bank)** based on personal, account, and transaction-related information.  
The objective of this project is to understand and implement a **complete end-to-end machine learning workflow**, from data analysis to model evaluation, using a real-world dataset.

---

## Dataset Used

- **Bank Customer Churn Dataset**
- Contains customer information such as:
  - Credit score
  - Age and gender
  - Account balance and number of products
  - Active membership status
- Target column: **Exited**  
  - `1` → Customer churned  
  - `0` → Customer retained  

---

## Project Structure
##### implementation_code.ipynb
##### Bank-Customer-Churn.csv
##### README.md

---

## Steps Followed in This Project

### 1. Data Loading and Understanding
- Loaded the dataset using Pandas
- Examined:
  - Dataset shape
  - Column names and data types
  - Missing and duplicate values
- Gained an understanding of each feature and its relevance

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed overall churn distribution
- Studied the relationship between churn and:
  - Age
  - Account balance
  - Credit score
  - Active membership status
- Identified patterns influencing customer churn

---

### 3. Data Preprocessing
- Converted categorical variables into numerical form
- Removed non-informative columns such as customer identifiers
- Scaled numerical features where required
- Split the dataset into **training and testing sets**

---

### 4. Model Building
- Trained machine learning classification models including:
  - Logistic Regression
  - Other suitable classifiers for comparison
- Focused on understanding model behavior rather than optimizing accuracy alone

---

### 5. Model Evaluation
- Evaluated model performance using:
  - Accuracy score
  - Confusion matrix
  - Classification report
- Compared results to identify the better-performing model

---

## Key Insights

- Older customers tend to have a higher churn rate
- Customers with low engagement are more likely to leave
- Proper feature preprocessing significantly impacts model performance

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## What I Learned

- Working with real-world structured datasets
- Performing meaningful EDA before modeling
- Building and evaluating classification models
- Understanding customer behavior through data analysis

---

## Author

**Shreyash More**
