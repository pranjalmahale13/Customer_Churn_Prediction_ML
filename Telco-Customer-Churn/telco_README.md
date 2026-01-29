# Telco Customer Churn Prediction Using Machine Learning

This project aims to predict whether a **telecom customer is likely to churn (stop using the service)** based on customer usage, subscription details, and billing information.  
The project was created to gain hands-on experience with a **complete machine learning pipeline**, starting from understanding the data and ending with evaluating different models on a real-world dataset.

---

## Dataset Description

- **Telco Customer Churn Dataset**
- The dataset includes various customer attributes such as:
  - Gender, tenure, and contract type
  - Phone and internet services
  - Monthly charges and total charges
- Target feature: **Churn**
  - `Yes` → Customer has churned  
  - `No` → Customer is retained  

---

## Project Workflow

### 1. Data Understanding
- Loaded the dataset and performed an initial inspection:
  - Total number of records and features
  - Data types of each column
  - Missing, null, or incorrect values
- Understood the purpose and importance of each feature

---

### 2. Exploratory Data Analysis (EDA)
- Studied how churn is affected by:
  - Contract type
  - Customer tenure
  - Monthly charges
- Used simple visualizations to observe trends and patterns
- Noted higher churn rates among customers on **month-to-month contracts**

---

### 3. Data Preprocessing
- Converted categorical features into numerical values
- Resolved data type issues where necessary
- Removed irrelevant columns such as customer ID
- Split the dataset into **training and testing sets**

---

### 4. Model Building
- Trained multiple classification models, including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Compared the performance of basic and advanced models

---

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy score
  - Confusion matrix
  - Classification report
- Compared results to determine the most effective model

---

## Key Learnings and Insights

- Customer tenure and contract type strongly influence churn behavior
- Ensemble models like Random Forest perform better than simpler classifiers
- Proper data preprocessing plays a major role in improving model results

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Project Structure

- `implementation_code.ipynb` – Notebook containing the complete implementation  
- `Telco-Customer-Churn.csv` – Dataset used in the project  
- `README.md` – Project documentation  

---

## Author

**Pranjal Mahale**
