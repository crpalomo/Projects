Purpose: Using sentiment analysis and machine learning to determine if an article headline is sarcastic.

Language: Python
Key Libraries: sklearn, spaCy, numPy, pandas, seaborn

Procedure:
1. Perform an exploratory data analysis (EDA) to profile the data.
2. Perform sentiment analysis using NLTK and spaCy
3. Create multiple models to determine which would be detector. Models include: Logistic Regression, Random Forest Classifier, K Nearest Neighbor, SVM
4. Uses multiple metrics to determine best model. Metrics include: Accuracy, f1-score, Precision, Recall
		
Conclusion:
Logistic Regression and SVM model preformed the best. Both models performed scored above a 0.9 in all metrics. The recommendation is to use the Logistic Regression model to which preformed slightly better in recall compared to the SVM. 
