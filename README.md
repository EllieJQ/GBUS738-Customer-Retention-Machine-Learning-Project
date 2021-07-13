# GBUS738-U.S. Telecommunication Customer Attrition Prediction
The telecom_df data frame contains information on the customers of a large U.S. telecommunications company which provides Internet and cellular service.  The company is looking to see if it can determine the factors that lead to customers canceling their service and whether it can predict if a customer will cancel their service in the future.  The company has experienced record levels of customers leaving their service in the past couple of years and this is leading to large financial losses.  The goal is to become better at identifying customers at risk of canceling their service to minimize financial losses.
Specifically, the broad questions that the company is trying to answer include:



What are the factors that are associated with customers canceling their service?
Is it possible to predict whether a customer will cancel their service? If so, how accurate are the predictions?
How many costly errors is the model expected to produce (customers classified as not canceling, but eventually do)?
Are there any actions or policies the company can implement to reduce the risk of service cancellation?


The data set contains a mixture of customer information (senior citizen indicator, presence of dependents, months with the company, etc..), and customer behavior (type of Internet and cellular service, average monthly call minutes, etc…)

The outcome variable in this data is canceled_service. This variable records whether a customer eventually canceled their service and indicates a financial loss to the company.
In first section of the project, an exploratory data analysis has been performed to explore the relationship between canceled_service and the other variables in the telecom_df data set. The goal of this analysis is to discover which variables drive the differences between customers who do and do not cancel their service.

In second section of the project, three classification algorithms are fit to predict the response variable,canceled_service. All the other variables in the telecom_df data are used as predictor variables for each model.

The final HTML output of this project can be accessed from the following link:
https://rpubs.com/EllieJQ/790228
