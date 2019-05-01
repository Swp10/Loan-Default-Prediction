# Loan-Default-Prediction
Lenders provide loans to borrowers in exchange for the promise of repayment with interest. That means the lender only makes profit if the borrower pays off the loan. However, if borrowers don't repay the loan, then the lender loses money.


Model Accuracies:
SVM Classifier           -- 83.51<br/>
Logistic Regression      -- 83.46<br/>
Decision Tree            -- 74.32<br/>
KNeighbors Classifier    -- 82.50<br/>
Random Forest Classifier -- 77.40<br/>

Apply one hot encoding<br/>
BSVM Classifier          -- 83.51<br/>
Logistic Regression      -- 83.40<br/>
Decision Tree            -- 74.06<br/>
KNeighbors Classifier    -- 81.94<br/>
Random Forest Classifier -- 83.14<br/>

SVM classifier has the highest accuracy, so I applied Grid Search.  ** My machine is not powerful enough to handle grid search calculation thus I am still waiting for the result.

SVM Classifier with grid search         -- WIP

Technologies:<br/>
Programming Language: Python<br/>
Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn<br/>
Visualization: plotly<br/>

Data Source:
https://www.kaggle.com/braindeadcoder/lending-club-data


