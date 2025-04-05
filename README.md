# Predicting Personal Loan Approvals with Logistic Regression Using Python, IBM SPSS, and Power BI
This project aims to predict personal loan approvals using a logistic regression model developed through a combination of Python (Scikit-learn), IBM SPSS, and Power BI. The objective was to identify significant factors that influence loan approval decisions and improve prediction accuracy for better banking operations.
The analysis was initiated in SPSS, where initial logistic regression modeling provided a baseline accuracy of approximately 90%. To further enhance the model’s performance and explore deeper insights, the data was preprocessed and the model was rebuilt in Python using libraries such as Pandas, Scikit-learn, Seaborn, and Matplotlib.

Key steps included:
Data normalization using StandardScaler
EDA and skewness analysis
Model training and evaluation using confusion matrix, classification report, and ROC-AUC score
Feature importance interpretation through logistic regression coefficients
Model enhancement using SMOTE and class weight balancing

The final model achieved a significantly improved accuracy of 95.2% and an AUC score of 0.96, indicating excellent discrimination between approved and non-approved cases. Key influencing factors included Income, Education, Family size, and Experience.

To visualize the impact and support business decisions, a Power BI dashboard was developed, presenting:
Comparison of model performance before and after improvements
Trendlines of key influencing features
Segment-wise loan approval probabilities

This comprehensive approach provides actionable insights for banks to optimize credit approval strategies and minimize risk by understanding patterns behind successful applications.


