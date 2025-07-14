#Bank-marketing-term-deposit-prediction
This dashboard is part of a machine learning project focused on predicting whether a customer will subscribe to a term deposit based on historical banking data. It effectively combines classification modeling, feature insights, and visual storytelling to support business decisions in customer targeting.

The dashboard was built using the following tools and technologies:
• Programming Language: Python
• Data Manipulation & Analysis: Pandas and NumPy
• Machine Learning & Modeling: Scikit-learn (for model training, evaluation, and prediction)Logistic Regression / Decision Tree / Random Forest
• Model Evaluation: Confusion Matrix,Accuracy, Precision, Recall, F1-Score,Probability thresholds
• Data Visualization: Matplotlib,Seaborn
• Dashboarding & Reporting: Tableau 
• Development Environment: Jupyter Notebook

DATA SOURCE:Kaggle(bank marketing dataset)

FEATURES/HIGHLIGHTS
• Business Problem
Predicting whether a customer will subscribe to a term deposit,helping banks run more targeted and cost-effective marketing campaigns.

• Goal Of The Dashboard
The dashboard aims to visually communicate the performance of a machine learning model built to predict customer subscription to term deposits. It highlights key influencing factors such as job type, contact method, call duration, and month of contact, providing actionable insights for marketing teams. By combining predictive analytics with intuitive visuals, the dashboard supports data-driven decision-making for more effective and targeted banking campaigns.

• Key Visuals and Insights

Actual vs Predicted Chart:
Description: Compares the model’s predictions against actual outcomes.
Insight: The model accurately predicts ~83% of "No" and ~89% of "Yes" cases, indicating strong performance.

Subscription Rate by Job:
Description: Shows subscription distribution across different job roles.
Insight: Customers in Management and Other roles have the highest subscription rates.

Call Duration vs Subscription:
Description: Plots subscription rate against call duration in seconds.
Insight: Calls longer than 200 seconds significantly increase the chances of a customer subscribing.

Monthly Subscription Trend:
Description: Displays subscription activity across different months.
Insight: May, August, and October see higher customer engagement and conversions.

Contact Method Success Rate:
Description: Compares success rates across contact methods (e.g., telephone, cellular).
Insight: Telephone contact shows lower success (~84% failure rate), suggesting it’s less effective.

Prediction Probability Distribution:
Description: Shows how confident the model is in its predictions.
Insight: Most predictions fall into high-confidence zones, proving the model is well-calibrated.

Overall Metrics Section:
Description: Summarizes total records, subscription percentage, and prediction accuracy.
Insight: Out of 3,349 customers, ~47% subscribed — a balanced dataset for modeling.

RESULTS AND INSIGHTS
• The machine learning model achieved high accuracy, correctly predicting ~83% of "No" and ~89% of "Yes" term deposit subscriptions.
• Out of 3,349 customers, around 47% subscribed to a term deposit — indicating a balanced dataset and meaningful target behavior.
• Call duration strongly influences subscription,customers who spoke for over 200 seconds were far more likely to subscribe.
• Customers in 'Management' and 'Other' job roles showed the highest subscription rates, while 'Housemaid' and 'Entrepreneur' had the lowest.
• Marketing campaigns performed best during May, August, and October, suggesting seasonal trends in customer responsiveness.
• Telephone contact had a high failure rate (~84%), making it the least effective channel compared to cellular or other methods.
• Most model predictions had high confidence levels, as seen in the probability distribution plot — indicating a well-calibrated model.
• The interactive dashboard provides clear visual insights into customer behavior and model performance, supporting better marketing decisions.











Ask ChatGPT


