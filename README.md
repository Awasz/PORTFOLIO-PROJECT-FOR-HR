# PORTFOLIO-PROJECT-FOR-HR


Employee Attrition Prediction and Retention Strategies
Project Overview
In this portfolio project, we aim to analyze employee data to predict attrition and provide recommendations for improving employee retention. The project focuses on Salifort Motors, a fictional French-based alternative energy vehicle manufacturer, with the goal of understanding the factors that contribute to employee attrition and suggesting data-driven strategies to enhance employee retention.

Business Case and Problem Statement
Salifort Motors is facing challenges related to employee attrition and wants to improve employee retention rates. Our objective is to analyze the employee data, build a predictive model, and provide actionable recommendations based on data insights to help Salifort Motors increase employee retention.

Data Description
We obtained a dataset from Kaggle, which contains 15,000 rows and 10 columns. The dataset includes features such as satisfaction level, last evaluation score, number of projects, average monthly hours, time spent with the company, work accidents, promotions in the last 5 years, department, and salary level.

Exploratory Data Analysis (EDA)
During the EDA phase, we performed a thorough analysis of the dataset to gain insights into the factors affecting employee attrition. Some key findings include:

Distribution of satisfaction level and its impact on attrition.
Correlations between different features and their relationship with attrition.
Identification of important features using feature importances from the Random Forest Classifier.
Model Development and Evaluation
We employed a Random Forest Classifier to predict employee attrition. The model was trained on a subset of the data and evaluated using various metrics such as accuracy, precision, recall, F1 score, and AUC-ROC score. The model exhibited high performance, achieving an accuracy of 97.87%.

Feature Importance and Interpretation
The feature importances obtained from the Random Forest Classifier revealed several key factors that contribute significantly to employee attrition. The top features impacting attrition include:

Time spent with the company
Job satisfaction level
Interaction between number of projects and average monthly hours
Data-Driven Recommendations
Based on the analysis and interpretation of the data, we provide the following recommendations to Salifort Motors for improving employee retention:

Focus on enhancing job satisfaction through initiatives like employee engagement programs and recognition schemes.
Monitor and manage workload by optimizing the number of projects and average monthly hours to prevent employee burnout.
Provide opportunities for career growth and professional development to increase employee engagement and commitment.
Conclusion and Future Steps
This portfolio project successfully analyzed the employee data, developed a predictive model for attrition, and generated data-driven recommendations for improving employee retention. Further steps could include:

Conducting additional analysis to explore the impact of other factors on attrition.
Comparing different machine learning algorithms to assess their performance.
Continuously monitoring and evaluating the implemented recommendations to measure their effectiveness.
References and Acknowledgments
Kaggle dataset: Link to the dataset
Python libraries used: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
