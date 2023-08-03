<div align="center">

  <h1 align="center">Predicting Employee Turnover</h3>

  <p align="center">
    <h3 align='center'>Recommendations on how to keep employees longer
    <br />
    <a href="#overview">Overview</a>
    .
    <a href="#business-understanding">Business Understanding</a>
    .
    <a href="#data-understanding-and-analysis">Data Understanding and Analysis</a>
    .
    <a href="#statistical-communication">Statistical Communication</a>
    .
    <a href="#conclusion">Conclusion</a>
  </p>
</div>


## Overview
For this project, you will use exploratory data analysis and statistical methods to generate insight for a business stakeholder.

## Business Understanding
Problem: The job market is evolving rapidly and companies are starting to see an increase in employee turnover.

Motivation: We want to better understand the variables that are associated with employee turnover and how we can reduce that outcome within a clients organization.

Exploration: We want to explore how machine learning can identify trends in the worplace. 

## Hypothesis
If our team can identify trends that correlate to a decrease in churn, we can make recommendations for an organization to implement ​

If our team can identify trends that correlate to a decrease in churn, we can make recommendations for an organization to implement and reduce employee turnover. reduce employee turnover. ​

To confirm these hypotheses, we’ll mainly look for higher model precision as an indicator of how successful our predictions are, given that we want a low false positive rate.​

## Data Understanding and Analysis
A dataset from kaggle titled "turnover.csv" was used to make these churn predictions. This dataset is compiled of categorical variables based on employee data. These variables include "industry", "profession", "coach", "wage", etc.
<!-- end of list-->

### Chosen Models
Logistic Regression 
- Logistic Regression is a statistical and machine learning algorithm used for binary classification tasks, where the goal is to predict one of two possible classes (e.g., yes/no, true/false, 0/1). Despite its name, logistic regression is a classification algorithm, not a regression algorithm.​
- The goal is to predict one of three possible classes ​(yes/no, true/false, 0/1)​
- Our accuracy was: 0.67

Random Forest 
- A Random Forest is an ensemble learning technique used in machine learning for both classification and regression tasks. It is based on the concept of creating multiple decision trees during the training phase and combining their predictions to make more accurate and robust predictions.​
- The goal is to create multiple decision trees during the training phase and combining their predictions to make more accurate and robust predictions.​
- Our accuracy was:  0.72​

### Model Metrics 
The random forest model we decided on was more precise than our logistic regression model.​

This means our model was more conservative and doesn’t usually overpredict. ​

When it predicts a positive (a person churning) it is highly precise, however it may miss out on other employees that may be likely to churn.

### Reccomendations
Based on the tests we conducted with our dataset we think these are the most impactful reccomendations to an organization 

Coaching- ​
Integrate a coaching system to help foster a community and onboard new employees into positive work culture. ​

Commuting​- 
Introduce commuter benefits program for employees, a company bus, or a carpool program to make employees a little more excited to journey to the office​.

Wages​- 
It costs more to hire a new employee than to pay a current one market wages. Make sure pay across the board is competitive to create satisfaction among your workforce​


## Conclusion
Organizations should impliment machine learning models with internal employee data to better understand how they can raitain their valuable employees.
