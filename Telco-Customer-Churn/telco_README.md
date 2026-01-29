# Telco Customer Churn Prediction

This project focuses on predicting whether a **telecom customer is likely to leave the service (churn)**.  
The project was built to practice and understand a **complete machine learning workflow** on a real-world dataset, from data understanding to model evaluation.

---

## Dataset Used

- **Telco Customer Churn Dataset**
- Contains customer-related information such as:
  - Gender, tenure, and contract type
  - Internet and phone services
  - Monthly charges and total charges
- Target column: **Churn**  
  - `Yes` → Customer churned  
  - `No` → Customer retained  

---

## Steps Followed in This Project

### 1. Data Understanding
- Loaded the dataset and examined:
  - Number of rows and columns
  - Data types
  - Missing and incorrect values
- Understood the meaning and relevance of each feature

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed how churn varies with:
  - Contract type
  - Customer tenure
  - Monthly charges
- Used basic visualizations to identify trends
- Observed higher churn among customers with **month-to-month contracts**

---

### 3. Data Preprocessing
- Converted categorical variables into numerical format
- Handled data type inconsistencies
- Removed non-informative columns such as customer identifiers
- Split the dataset into **training and testing sets**

---

### 4. Model Building
- Trained multiple classification models, including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Compared simple and more advanced models

---

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy
  - Confusion matrix
  - Classification report
- Compared performance to identify the better-performing model

---

## Key Learnings

- Customer tenure and contract type are strong indicators of churn
- Ensemble models such as Random Forest perform better than simpler models
- Proper preprocessing has a significant impact on model performance

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Project Structure
##### implementation_code.ipynb
##### Telco-Customer-Churn.csv
##### README.md

---

## Author
**Shreyash More**   