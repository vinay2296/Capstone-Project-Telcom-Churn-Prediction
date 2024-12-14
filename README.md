Telecom Churn Prediction
Telecom companies aim to predict which customers are at high risk of churn, and in this project, the goal is to:

Analyze customer-level data from a leading telecom provider.
Build machine learning models to identify customers at high risk of churn.
Identify key indicators that contribute to customer churn.
Data Overview
The dataset includes customer-level data spanning four consecutive months: June (Month 6), July (Month 7), August (Month 8), and September (Month 9). The objective is to predict whether a customer will churn in September (Month 9) based on their behavior in the first three months (June, July, and August).

In churn prediction, customers are categorized into three lifecycle phases:

1) The ‘Good’ Phase: During this phase, the customer is satisfied with the service and exhibits typical behavior.
The ‘Action’ Phase: This phase marks a decline in customer satisfaction, often triggered by external factors such as a competitor’s offer, service quality issues, or unjust charges. It's crucial to identify high-churn-risk customers in this phase so that corrective measures can be implemented, such as offering competitive deals or improving service quality.
2) The ‘Churn’ Phase: This phase occurs when the customer has already churned. It's important to note that data from the churn phase is unavailable at the time of prediction. Therefore, churn (1 or 0) is labeled based on the behavior in the churn phase, and data from this phase is excluded from the prediction model.
In this dataset, the first two months (June and July) represent the ‘good’ phase, the third month (August) is the ‘action’ phase, and the fourth month (September) represents the ‘churn’ phase. The goal is to predict churn based on the data from the first three months.
