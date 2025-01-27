# Machine-Learning-Project-Classification-of-Loan-Status-Using-ML-Algorithms-

In this project, I performed several steps to prepare the data and evaluate various machine learning models to predict loan outcomes.

Data Preprocessing:

Cleaned and transformed the raw data to make it suitable for modeling. This included handling missing values, encoding categorical variables, and normalizing numerical features.
Modeling:

Applied different machine learning models to the processed data to predict the loan outcomes. The models tested included:
K-Nearest Neighbors (KNN): A non-parametric method used for classification based on the closest training examples.
Decision Tree: A tree-like model used for classification and regression, splitting data based on feature thresholds.
Support Vector Machine (SVM): A supervised model that finds the optimal hyperplane for separating classes.
Logistic Regression: A statistical model that uses a logistic function to model the probability of a binary outcome.
Model Evaluation:

After training and testing all models, the SVM model showed the highest accuracy for predicting loan outcomes. This means that the SVM model outperformed the others in terms of making correct predictions.


| Algorithm          | Jaccard | F1-score |
|--------------------|---------|----------|
| KNN                | 0.67    | 0.63     |
| Decision Tree      | 0.72    | 0.74     | 
| SVM                | 0.80    | 0.76     |
| LogisticRegression | 0.74    | 0.66     | 
