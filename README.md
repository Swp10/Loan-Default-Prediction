# Loan-Default-Prediction
Lenders provide loans to borrowers in exchange for the promise of repayment with interest. That means the lender only makes profit if the borrower pays off the loan. However, if borrowers don't repay the loan, then the lender loses money.


Model Accuracies:
SVM Classifier           -- 83.51
Logistic Regression      -- 83.46
Decision Tree            -- 74.32
KNeighbors Classifier    -- 82.50
Random Forest Classifier -- 77.40

Apply one hot encoding
BSVM Classifier          -- 83.51
Logistic Regression      -- 83.40
Decision Tree            -- 74.06
KNeighbors Classifier    -- 81.94
Random Forest Classifier -- 83.14

SVM classifier has the highest accuracy, so I applied Grid Search.  ** My machine is not powerful enough to handle grid search calculation thus I am still waiting for the result.

SVM Classifier with grid search         -- WIP

Technologies:
Programming Language: Python
Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn
Visualization: plotly

Data Source:
https://www.kaggle.com/braindeadcoder/lending-club-data


