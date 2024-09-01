
# Project Overview

### Problem statement

SyriaTel, a telecommunications company, is facing a high churn rate, with many customers discontinuing their services and switching to competitors. By analyzing the dataset, SyriaTel aims to gain insights into factors associated with high customer churn, leading to significant revenue loss

### Objectives are:

- Identify the factors that are most likely to lead to customer churn.

- Develop a model that can accurately predict which customers are at risk of churning.

- Take proactive steps to retain customers who are at risk of churning.

My stakeholders are:
- SyriaTel company

- Potential Investors

- Partners of SyriaTel 

By analyzing customer data and identifying key factors contributing to churn, our project offers valuable insights for telecom businesse. These insights can be used to implement targeted strategies to improve customer satisfaction, reduce churn rates, and ultimately increase revenue. 

## Data understanding
We source our data from Kaggle: Churn in Telecom's dataset. These data sources are well-suited for this project because they provide a comprehensive understanding of customer behavior, service usage, and factors that may contribute to churn.

## Data Preparation
In this phase, the dataset was cleaned, relevant features were extracted, and appropriate transformations were applied for modeling.

##Modeling
To begin, we point out that the dataset is imbalanced, with only 14.5% of the data being classified as "churn" and the rest being classified as "not churn."

Our baseline model was LogisticRegression , just to test how our chosen attributes would perform on a basic level. We then explored other models like Decision trees,

## Evaluation
DecisionTreeClassifier has the highest recall score.
The ROC curve analysis shows that the DecisionTreeClassifier has the best performance.

## Model Tuning
We focused on improving the performance of DecisionTreeClassifier models. After conducting hyperparameter tuning , we evaluated the models based on the recall score.

## Recommendations
1.Improve customer service quality and reduce the number of customer service calls. Enhance training programs for customer service representatives to ensure prompt and effective resolution of customer issues, leading to higher customer satisfaction and reduced churn.

2.Evaluate the pricing structure for day, evening, night, and international charges. Consider adjusting pricing plans or introducing discounted packages to address the higher charges associated with customers who churn.

3.Invest in improving international connectivity by offering more international plans, offering free international calls, and providing better international service quality.

4.Improve customer retention by offering loyalty programs, free or discounted services, and incentives for repeat business. This can help retain customers and improve customer loyalty.

5.Monitor and analyze customer churn patterns to identify trends and areas for improvement. This will help in making data-driven decisions to optimize customer retention and improve customer satisfaction.

6.Enhance the value proposition of the voicemail plan to increase adoption among customers. Highlight the benefits and convenience of voicemail services, and consider offering additional features or discounts to encourage customers to sign up.

7.Educate the customers on the benefits of the voice mail

## Conclusion
In conclusion, the analysis of the customer churn in SyriaTel has provided clear knowledge on the factors that leads to churning of the customers as well as valuable insights into the customer behaviors.

The models have provided a clear predictive power on customers churn as well as identifying important features that greatly influence customer retention.

## Next steps
Focus on the customer satisfaction. This will ensure that the customers who have not churned are always enjoying the services of the company and that at no point will they discontinue with the usage of the company’s services and products

Implement a customer feedback system that allows customers to share their experiences and suggestions for improvement. This will help the company gather valuable feedback and make data-driven decisions to improve customer satisfaction and retention

Analyze the customer churn patterns to identify trends and areas for improvement


