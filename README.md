# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Description:

In this project, the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases was utilized to gain insights and develop a predictive model. The following steps were as below:

Exploratory data analysis and pre-processing: The dataset was imported and underwent thorough data cleaning processes. Relationships between different variables were analyzed and visualized to gain insights into the data. Additionally, steps were taken to handle missing values and outliers effectively.

Model building: Three machine learning models were constructed, including the Random Forest Model, Decision Tree model, and XGBoost. Each model was trained and evaluated based on their performance metrics. After comparing the models, it was observed that the Random Forest model outperformed the others in terms of accuracy.

By following these steps, the project aimed to harness the power of data analysis, visualization, and machine learning to gain valuable insights from the "Diabetes" dataset and build an accurate predictive model for diabetes.

### Key Finds:

Based on the machine learning models developed and the exploratory data analysis (EDA) conducted for diabetes modeling, here are four key findings:

1. EDA: When analyzing the data, it is crucial to pay attention to zero values. It is important to understand the units of each column and determine the normal
range to gain insights into potential outliers. Before decided the outlier, I searched up if the max value of Insulin and Glucose are reasonable.

2. Data Patterns: Exploratory data analysis revealed patterns and correlations within the diabetes dataset. For instance, there was a positive correlation 
between glucose level and diabetes diagnosis, indicating that higher glucose levels are associated with an increased risk of diabetes. Additionally, factors
like BMI and age showed some degree of correlation with diabetes occurrence.

3. Feature Importance: The Random Forest model identified certain features as significant predictors of diabetes. These features, such as glucose level, 
body mass index (BMI), and age, exhibited higher importance in influencing the model's predictions. 

4. Model Performance: Among the three models compared, the Random Forest model outperformed the others in terms of accuracy. This suggests that the ensemble 
approach employed by Random Forest, which combines multiple decision trees, can effectively handle the complexity of the diabetes dataset and yield more
accurate predictions.