# Loan_Eligibility_Prediction
### Overview :
This repository contains an end-to-end project focusing on predicting house loan eligibility. The project includes thorough Exploratory Data Analysis (EDA) performed using Tableau to visualize and analyze the dataset. The main objective is to develop predictive models using both XGBoost and Artificial Neural Network (ANN) algorithms to determine whether an individual is eligible for a house loan or not.

Kaggle link : https://rb.gy/v19bmg

Tableau link : https://public.tableau.com/app/profile/yasmine.jalil/vizzes
  ### EDA with Tableau :

 ![](images/dashboard.PNG)

### EDA with python :
-->Check out Customer_churn_prediction.ipynb
### Insights 🔮
- Short-term contracts, notably month-to-month, result in a significant increase in churn rates.
- Two-year contracts showcase a commendably low churn rate.
- Customers with a one-year tenure experience a substantial decrease in churn, emphasizing the value of longer relationships.
- Electronic check payments are associated with a higher churn rate, while credit card payments provide stability.
- Customers without internet service display an impressively low churn rate.
- However, those with Fiber Optics internet service are more likely to churn.
- The senior citizen demographic exhibits a higher churn rate.
- Emphasizing additional features like Security, Backup, Device Protection, and Tech Support reduces churn likelihood effectively.
  
### Model Training Results :

Both models are giving very good performance and their accuracy seems to be very close to each other with ANN leading in terms of performance. 
#### - ANN :
  
 ![](images/cr_1.PNG) 

 ### Flask App :
<details>
  <summary>Click to expand</summary>
- Form page to input users data :

 ![](images/form.PNG)
 
 - Prediction results :
   
 ![](images/2.PNG)
</details>
