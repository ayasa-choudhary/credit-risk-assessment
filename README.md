# **Credit Risk Assessment**

This project focuses on assessing credit risk using a dataset named **credit-data**. The goal is to analyze various factors influencing credit risk, such as age, income, employment length, loan amount, and credit history, and to predict outcomes using machine learning techniques.

---

## **Key Features of the Analysis**

### **1. Exploratory Data Analysis (EDA)**
- Performed EDA to understand the structure and distribution of the dataset.  
- Operations include:
  - **Shape**: Understanding the size of the dataset.
  - **Columns**: Listing all the dataset columns.
  - **Value Counts**: Analyzing categorical variables.
  - **Info**: Reviewing data types and missing values.
  - Visualization of data distributions using box plots.

### **2. Data Visualization**
- Visualized data relationships and distributions using:
  - **Pair Plot**: Created using `sns.pairplot` to observe relationships between multiple numerical features.
  - **Box Plot**: Used to analyze the distribution and outliers of numerical data.
  - **Scatter Plot**: Generated using `plt.scatter` for targeted variable comparisons.

### **3. Machine Learning**
- Splitting data into training and testing sets using `train_test_split`.  
- Built a prediction model using **Support Vector Regressor (SVR)** from `sklearn`.  
- Performed predictions to estimate credit risk.

---

## **Dataset Columns**
The **credit-data** dataset includes the following columns:  
1. **person_age**: Age of the individual.  
2. **person_income**: Annual income of the individual.  
3. **person_emp_length**: Employment length in years.  
4. **loan_amnt**: Loan amount requested by the individual.  
5. **loan_int_rate**: Interest rate applied to the loan.  
6. **loan_status**: Status of the loan (approved, rejected, etc.).  
7. **loan_percent_income**: Percentage of income being allocated to loan repayment.  
8. **cb_person_cred_hist_length**: Length of the individual's credit history. 
