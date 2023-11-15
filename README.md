# CUSTOMER-CHURN-PREDICTION-MACHINE-LEARNING-MODEL

![image](https://github.com/dapzwalt/CUSTOMER-CHURN-PREDICTION-MACHINE-LEARNING-MODEL/assets/125368548/91b93b6f-4291-4232-9da3-c2d070b169c9)

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Model Optimization](#model-optimization)
- [Key Insights](#key-insights)
- [Challenges](#challenges)
- [Conclusion](#conclusion)

## Project Overview
Connectel telecom company faces the pressing need to address customer churn, which poses a significant threat to its business sustainability and growth. The company's current cutomer retention strategies lacks precision and effectiveness resulting to the valuable loss of customers to competitors

## Project Objective
The aim of this project is to develop a robust customer churn prediction system by leveraging advanced analytics and machine learning techniques on available customer data in order to accurately forecast customer churn and implement targeted retention initiatives 

## Data Sources
The dataset used in this project was provided by Connectel telecom company. The dataset contains a collection of features extracted from the company database which includes features as 
gender, customer ID, tenure, streaming TV, online service, dependents, partners and other relevant information

## Exploratory Data Analysis
I performed data wrangling, conducted univariate and bivariate analysis, showing correlations between variables and drawing out inferences. checked for missing values and duplicates in my dataset. Most importantly, feature engineering was performed to extract relevant information from my raw data

## Data Preprocessing
I performed exploratory data analysis, encoding of categorical variables, normalization of my data which entails scaling the features before feeding the data into the machine learning model.

## Machine Learning Model
The customer churn prediction model is built using a supervised machine learning approach. Training and testing of my data was done by splitting my data to the ratio 25:75. Several classification algorithms were employed which includes:

- **Logistic Regression**
- **Decision Trees**
- **K-Nearest Neighbors**
- **Support Vector Machine**

## Evaluation Metrics
The following evaluaton metrics were used to assess the performance of the individual machine learning algorithms, which are: 

- **Precision:** This shows that when it predicts that customers has not cancelled their service with the company
- **Recall:** This shows the customer churn true positive rate.
- **F1score:** This is the harmonic mean of precision and recall, thus providing a balanced metric for model evaluation
- **Accuracy:** Accuracy shows how good the model performed but is not a final resort to determining or choosing the best model
  
## Model Optimization
After extensive experimentation and hyperparameter tuning, the model with the highest score in terms of its classification report was chosen based on its performance and generalized capabilities.

## Key insights
- The purpose of this project is to predict customer churn
- After subjecting the models to evaluation metrics like the accuracy, recall, precision and f1score, the best performing model was chosen which is the SVM because we had lesser error with this model
- From the confusion matrix, True positives, a total of 958 customers did not churn meaning they didn't cancel their service and the algorithm predicted right. False negatives a total of 198 customers did not churn meaning that they didnt cancel their service and the algorithm predicted that they churn. So I would advice the company to be more concerned about the true positives. 

## Challenges
The challenge I faced in this project was to manage my time in carrying it out without errors. Customer behavior is dynamic and can change over time. Patterns that were relevant in the past may not hold in the future, making it challenging to build models that generalize well. Also selecting the right features or variables that contribute most to predicting customer churn is not always straightforward. Choosing irrelevant or redundant features can lead to suboptimal model performance.

## Conclusion
Customer churn uses machine learning model to predict whether customers are using the telecom service or not. More like customer attrition. In this project, we are able to see how various features contributes to the retention of customers on the product like customers with dependents more on the service than customers without dependent, also saw that customers who had partners were more using the telecom service than those without partners. By accurately forecasting customer churn, the company will be able to make plans as to how to keep the remaining customers and not lose more and also make loyalty programs to keep existing ones and know the signs that a customer is about to stop using the service. If there is need for more advert to bring in more customers, Then marketing campaigns needs to be done by the sales and marketing department of the comapany.
Support Vector Machine did best in predicting customer churn, looking through the jupyter notebook posted will explain more better as I made it step by step for your understanding. However, if there are adjustment to be made or corrections, kindly drop it in. 
Additionally, for production at the backend users like the software developers, an output for software has been made also. Enjoy 
