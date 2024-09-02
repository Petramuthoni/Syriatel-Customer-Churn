# Syriatel-Customer-Churn
# Business Understanding
In response to increasing competition, technological advancements, and globalization in the telecommunications market, Syriatel Mobile Telecom has emphasized the importance of enhancing customer satisfaction and retaining its customers. The company reaffirms its commitment to maintaining its market position by prioritizing customer satisfaction and social responsibility.

While these efforts have been successful, Syriatel must further intensify its focus on reducing customer churn rates to safeguard its market position, profitability, and growth. Retaining its customer base will help the company reduce costs, prevent losses, and boost sales. Additionally, it will increase ROI, lower marketing expenses, enhance customer loyalty, and encourage new customer acquisition through referrals.

This project will enable Syriatel to identify customers most likely to churn, allowing the company to implement strategic policies to ensure retention.The project will focus on identifying potential churners within Syriatel's customer base and making strategic business decisions to retain them

As the primary stakeholder, Syriatel stands to benefit from this model by reducing customer churn rates, leading to increased revenues, profits, and market position. Customers will enjoy enhanced telecommunication services and improved customer support. As the company grows through higher revenues, profits, and market share, shareholders will see increased returns on their investments, and employees will benefit from better compensation and bonuses.

This project seeks to deliver value to all stakeholders by identifying patterns in customer churn, enabling Syriatel to take proactive measures to retain customers and minimize revenue loss.
# Objectives:

To Find out the key features that determine if a customer is likely to leave.
To Find out the most suitable model to predict Customer Churn.
To determine Customer retention strategy to reduce churning
# Data Understanding
The Churn in Telecom dataset from Kaggle provides information on customer activity and whether they canceled their subscription with the telecom company. The goal of this dataset is to develop predictive models that can help the telecom business reduce revenue losses due to customer churn.

The dataset consists of 3,333 entries and 21 columns, including details such as state, account length, area code, phone number, international plan, voice mail plan, usage statistics, customer service calls, and churn status.
# Data Preparation
In this section,several actions are taken to prepare our data for exploratory data analysis and modelling. The actions include importing all the necessary libraries, loading the dataset using pandas library, previewing the data and conducting thorough data preprocessing.
# Modeling and Evaluation
I created two models,that is, Logistic regression model and Decision Tree model.Logistic regression model is the base model.Decision tree model has a better performance compared to the logistic regression model.Decision tree has an accuracy of 94.8%.
In conclusion, the analysis suggests that we can accurately predict customer churn using a machine learning model, with the Descision Tree Classifier being the recommended model due to its strong overall performance. As this is the best performing model with an ROC curve that is on the upper left corner of the graph, hence giving us the largest AUC (Area Under the curve).
# Conclusion and Recommendations
I would recommend that Syriatel uses the Descision Tree Classifier as the primary model for predicting customer churn. This model has a higher ROC curve and strong overall performance in terms of accuracy and F1-score on the test set, making it well-suited for accurately classifying customers as likely or unlikely to churn.

In terms of Business strategic recommendations for SyriaTel, I would recommend a Customer Retention strategy that addresses key features in relation to call minutes and charges. These efforts could include personalized offers or discounts on day charges. By implementing cost-effective strategies that address the key factors driving customer churn, SyriaTel can retain customers and minimize revenue loss.

I would recommend, that Syriatel comes up with strategies to reduce on Customer Service calls, as this is among the top features that would likely lead to Customer Churn.
