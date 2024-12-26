# Predicting Customer Churn Using K-Nearest Neighbors (KNN)

## Overview
This project focuses on predicting customer churn in the banking industry using the K-Nearest Neighbors (KNN) algorithm. Customer churn is a critical challenge, as retaining customers is more cost-effective than acquiring new ones. By accurately identifying customers who are likely to churn, banks can take proactive steps to enhance customer retention strategies.

## Objective
The goal of this project is to develop a predictive model that identifies customers at risk of churn based on demographic, financial, and engagement data. The KNN classifier is implemented from scratch to ensure a deep understanding of the algorithm and its components.

## Key Features

### Data Preprocessing
- Addressed missing values and scaled numerical features for improved model performance.
- Analyzed categorical and numerical variables to determine their relevance in predicting churn.
- Conducted feature engineering to enhance the quality and predictive power of the dataset.

### Model Development
- Built the K-Nearest Neighbors (KNN) classifier without relying on pre-built libraries.
- Experimented with various values of `K` to optimize the model’s performance.
- Tuned hyperparameters, including distance metrics (Euclidean, Manhattan), to improve accuracy.

### Model Evaluation
- Evaluated performance using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
- Performed cross-validation to prevent overfitting and ensure generalization to unseen data.

## Dataset Details
The dataset contains the following attributes:
- **Customer ID**: Unique identifier for each customer.
- **Surname**: Customer’s last name.
- **Credit Score**: A numerical indicator of the customer's creditworthiness.
- **Geography**: Country of residence (France, Spain, or Germany).
- **Gender**: Customer's gender (Male or Female).
- **Age**: Customer's age.
- **Tenure**: Duration of the customer’s relationship with the bank (in years).
- **Balance**: Account balance.
- **NumOfProducts**: Number of products the customer uses (e.g., savings account, credit card).
- **HasCrCard**: Indicator of credit card ownership (1 = Yes, 0 = No).
- **IsActiveMember**: Indicator of active membership (1 = Yes, 0 = No).
- **EstimatedSalary**: Customer’s estimated annual salary.
- **Exited**: Whether the customer has churned (1 = Yes, 0 = No).

## Results
The model demonstrated robust predictive performance, successfully identifying customers at risk of churn. Insights gained from this project can be applied to real-world banking scenarios to improve customer retention strategies.

## Future Work
- Experiment with advanced algorithms such as Support Vector Machines (SVM) and Random Forests to compare performance.
- Incorporate additional customer interaction data, such as transaction frequency, to further refine the model.
- Deploy the model as a web application to provide churn predictions in real-time.

## Conclusion
This project highlights the potential of data-driven solutions in addressing critical business challenges. The implementation of the KNN algorithm from scratch not only provided valuable insights into its workings but also underscored the importance of feature engineering and hyperparameter tuning in achieving high-quality predictions.
