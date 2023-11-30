# [Capstone 3 JCDS Purwadhika]

**Preface**

This project is created as an exercise and to complete my Capstone Module 3 Project of Data Science bootcamp in Purwadhika,
and also serves as a preview of my work and marks my learning journey of becoming a full fledged Data Scientist.

Feel free to give any feedbacks and reach out to me via [email](ghany.salam12@gmail.com) or connect with me on [LinkedIn](www.linkedin.com/in/ghanysalam/)

## Before you dive in
This project comprises of several part in different format:
1. [Jupyter Notebook](https://github.com/ghanysalam/Capstone-3-Travel-Insurance-Prediction-Claim/blob/main/Capstone%203-%20Travel%20Insurance%20-%20Prediction%20Claim.ipynb) for more detailed
2. [Case Study](https://www.kaggle.com/datasets/mhdzahier/travel-insurance)
3. [Video Presentation](https://drive.google.com/file/d/1aDK0rNvL-H7BiXsrLOXBLZlj3OYTfBls/view?usp=drive_link)
4. [Machine Learning Model](https://github.com/ghanysalam/Capstone-3-Travel-Insurance-Prediction-Claim/blob/main/xgb_model.pkl)

# **Background**
Travel insurance is a type of insurance that provides protection while we are traveling both domestically and internationally. Some countries even require travelers to have travel insurance, for example, countries in Europe and America. The amount of the premium depends on the desired coverage, the journey, and the travel destination. A company that operates in travel insurance wants to know which policyholders will have their insurance claims accepted. This will help reduce the burden, performance, and time as well as the quality of service of travel insurance providers to travelers.

## **Target**

No (0): Insurance owner does not makes a claim

Yes (1): Insurance owner makes a claim


## **Problem Statement**

The current marketing strategy is inefficient because it does not differentiate customers, resulting in the waste of resources and the loss of engagement opportunities from prospective customers. The company wants to effectively differentiate and target potential customers who are likely to make a claim, thereby optimizing resources and increasing customer satisfaction.

## **Goals**

Based on the problem, the company wants to implement a predictive model to differentiate customers based on the likelihood of their claims being accepted, thus not wasting marketing time and costs unnecessarily.

In addition, the company wants to identify factors that influence claim approval to improve decision-making processes and customer service.

## **Metric Evaluation**

1. True Positive: Traveler makes a Claim and the model predicts a Claim will be made
2. False Positive: Traveler does not make a Claim, but the model predicts a Claim will be made
3. False Negative: Traveler makes a Claim, but the model predicts no Claim will be made
4. True Negative: Traveler does not make a Claim and the model predicts no Claim will be made

- Error type 1 (False Positive):
Consequences: Marketing costs and company resources are wasted.

- Error type 2 (False Negative):
Consequences: Loss of potential prospects.

Based on the consequences of each type of error, the main focus of the model we will create is to minimize Error type 2 because the consequences of False Negatives are more serious than False Positives (Type I error). This type 2 error has the potential to reduce company revenue due to the loss of potential customers. So, the main metric we will use later is the recall score.

# Project Features

- Data Cleaning (Missing Values, Duplicate Values and Outliers)
- Data Analysis
- Feature Selection and Engineering (Encoding and Scaling)
- Modeling, Analytics, and Evaluation (Recall Score, XGBoost, and Hyperparameter Tuning)
- Conclusion and Recomendations
