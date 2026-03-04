#  Customer Churn Prediction

##  Week 1: Exploratory Data Analysis (EDA)

This project focuses on analyzing customer behavior to understand the key factors influencing churn using the Telco Customer Churn dataset.

---

##  Dataset

- **Source:** Telco Customer Churn Dataset  
- **Size:** 7,043 customers  
- **Features:** 21 input features  
- **Target Variable:** `Churn` (Yes/No)  

**Objective:** Predict whether a customer is likely to churn.

---

##  Project Files

- `week1_eda.ipynb` – Exploratory Data Analysis notebook  
- `customer_data.csv` – Dataset *(not included in repository; download separately)*  

---

##  Key Findings

1. **Churn Rate:**  
   26.54% of customers have churned, while 73.46% remained with the company.

2. **Tenure is the Strongest Predictor:**  
   Customers with longer tenure are significantly less likely to churn, showing a strong negative correlation.

3. **Monthly Charges Impact Churn:**  
   Higher monthly charges are associated with increased churn probability.

4. **Senior Citizens Churn More Frequently:**  
   Senior customers demonstrate a higher likelihood of churn compared to non-senior customers.

5. **Data Quality Note:**  
   The `TotalCharges` column contained 11 missing values, which were identified and require cleaning before model development.

---

##  Project Roadmap

- **Week 2:** Build machine learning models  
- **Week 3:** Model evaluation & optimization  
- **Week 4:** Deploy an interactive dashboard  

---

## Setup Instructions

Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
