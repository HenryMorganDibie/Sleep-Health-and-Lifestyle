# Sleep-Health-and-Lifestyle
## Exploratory Data Analysis (EDA) Summary:
1. Age Distribution:
Insight: The dataset includes individuals between 27 and 59 years old, with a relatively even distribution. A slight decline in numbers is observed after the age of 50.
2. Sleep Duration:
Insight: Sleep duration is positively skewed, with the majority reporting between 5 to 8 hours. There are a few instances of sleep durations below 5 hours.
3. Correlation Analysis:
Insight: Positive correlation between age and sleep duration suggests that older individuals tend to sleep longer. Negative correlation between stress level and sleep duration implies that higher stress may be associated with shorter sleep.
4. Sleep Disorders:
Insight: Insomnia is the most prevalent sleep disorder, followed by No Sleep Disorder and Sleep Apnea. The distribution varies across different age groups.
5. Occupation Analysis:
Insight: Nurses and teachers exhibit higher occurrences of sleep disorders. Other professions, such as accountants, engineers, and doctors, also show significant instances of sleep disorders.
6. BMI Category and Sleep Duration:
Insight: Individuals categorized as "Obese" tend to have slightly shorter sleep durations. Other BMI categories (Normal, Normal Weight, Overweight) show comparable sleep durations.
7. Gender and Sleep Disorders:
Insight: Females exhibit a higher prevalence of sleep disorders compared to males. Insomnia is more common among females, while Sleep Apnea is more prevalent in males.
8. Feature Importance:
Insight: Key features influencing sleep disorder prediction include BMI category, age, sleep duration, physical activity level, stress level, and gender.
9. Cross-Validation:
Insight: Cross-validation scores indicate variability in model performance across different train-test splits. The mean cross-validation score provides an overall assessment of the model's generalization capability.
## Predictive Modeling:
1. Data Preprocessing:
Breakdown: Handled missing values, encoded categorical features, and standardized numerical features.
2. Model Selection:
Breakdown: Explored three models - Neural Network, Random Forest, and XGBoost for sleep disorder prediction.
3. Model Training and Evaluation:
Breakdown: Trained models, evaluated on training and testing sets, and performed hyperparameter tuning for Random Forest.
4. Model Comparison:
Results: Random Forest outperformed Neural Network and XGBoost, achieving a testing accuracy of 92%.
5. Feature Importance and Interpretation:
Results: Identified key features influencing sleep disorder prediction, with BMI category, age, and sleep duration being the most significant.
6. Ensemble Model:
Results: An ensemble model combining Random Forest, Neural Network, and XGBoost achieved a testing accuracy of 92%.
Conclusion:
The insights from EDA provided a comprehensive understanding of the dataset, guiding feature selection and interpretation. The predictive models, especially Random Forest, demonstrated good performance in sleep disorder prediction. The ensemble model further enhanced predictive capabilities. The key features identified in the analysis can be valuable for interventions or recommendations related to sleep health.
