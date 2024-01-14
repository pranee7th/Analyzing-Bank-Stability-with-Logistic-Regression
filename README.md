Data Overview:
Response Variable: Financial Condition (Weak/Strong)
Predictors: TotLns&Lses/Assets, TotExp/Assets
Data Preprocessing:
The dataset is loaded and checked for missing values, followed by exploratory data analysis using correlation matrices to ensure no highly correlated predictors. The dataset is then split into training and testing sets for model evaluation.

Logistic Regression Modeling:
A Logistic Regression model is trained on the entire dataset, modeling the bank's financial condition as a 
function of the two financial measures. The success class is specified as weak, and the default cutoff value of 0.5 is used for classification.

Model Evaluation:
The accuracy of the model is evaluated on the test set, yielding a classification accuracy score. 
The logistic regression model's estimated equations are presented in terms of the logit, odds, and probability functions.

Classification of New Bank:
The trained model is used to estimate the financial condition of a new bank with given ratios. 
The logit, odds, probability, and classification of the new bank are computed based on the logistic regression model.

Cutoff Value Analysis:
The project explores the impact of changing the cutoff value for classification on the misclassification error.
Different cutoff values are tested to find an optimal threshold that minimizes misclassification costs.

Conclusion:
The Logistic Regression model proves effective in predicting the financial condition of banks based on the provided financial ratios. 
The project concludes with insights into the misclassification costs and recommendations for selecting an appropriate cutoff value to optimize model performance.
