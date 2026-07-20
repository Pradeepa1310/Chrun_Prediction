 Bank Customer Churn Prediction Using Machine Learning

 Overview

This project predicts whether a bank customer is likely to leave the bank (churn) using Machine Learning techniques. The model is trained on customer demographic and banking information and classifies customers into two categories: **Exited** or **Stayed**.

 Domain

Banking and Financial Services

 Problem Statement

Customer churn is a significant challenge for banks. This project aims to build a Machine Learning model that can predict customer churn based on customer attributes and account information, helping banks improve customer retention strategies.

 Dataset

**Dataset Name:** Churn_Modelling.csv

 Features

* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary

Target Variable

**Exited**

* 0 = Customer Stayed
* 1 = Customer Left the Bank

 Technologies Used

* Python
* Pandas
* Scikit-learn
* NumPy

Machine Learning Algorithm

* Random Forest Classifier
  
 Project Workflow

1. Load the dataset
2. Clean and preprocess data
3. Encode categorical variables
4. Split data into training and testing sets
5. Train the Random Forest model
6. Evaluate model performance
7. Predict customer churn

 Installation

Install the required libraries:

```bash
pip install pandas scikit-learn
```

 Running the Project

Run the Python script:

```bash
python churn_prediction.py
```

 Expected Output

```text
Accuracy: 0.86%
```

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/1409694d-3977-4650-a0fa-a0d53eaae082" />


The exact accuracy may vary slightly depending on the train-test split and model parameters.

## Performance Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

Project Structure


 Applications

* Customer Retention Analysis
* Banking Analytics
* Customer Relationship Management
* Business Decision Support

 Future Enhancements

* Hyperparameter Tuning
* XGBoost Implementation
* SMOTE for Imbalanced Data
* Deployment using Flask or Streamlit
* Real-Time Churn Prediction

Conclusion

This project demonstrates the use of Machine Learning in predicting customer churn within the banking sector. By identifying customers likely to leave, banks can take proactive measures to improve customer satisfaction and retention.

 Author

Pradeepa D

