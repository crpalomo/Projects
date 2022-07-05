Purpose: The purpose of the project is to develop a machine learning model that will aide in the prediction of Kepler Objects of Interests (KOI). This includes performing an exploratory data anlysis of the complete data set, feature selection, and developing various models using different classifiers.

Language: Python, R

Key Libraries: numPy, pandas, rpy2, sklearn

Procedure:

1. Perform an exploratory data analysis (EDA) using R programing language through rpy2 library.
2. Prepare the data for machine learning.
3. Use backward elimination for feature selection.
4. Create and test three models. Models include: Logistic Regression, Random Forest Classifier, and Niave Bayes Classifer

Conclusion: Based on the results we can see that the Random Forest classifer yeilds the best results compared to the other models. Only incorrectly predicting 21 cases out of the 2761 within the test data set. This gave the overall results to be 0.99 in precision, recall, and f1-score. Due to how well the model preformed further analysis is need to ensure the accuracy of the model.
