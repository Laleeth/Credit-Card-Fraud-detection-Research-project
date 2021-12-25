# Credit-Card-Fraud-detection-Research-project
Research project



#### Problem Statement: Companies need to identify fraudulent credit card transactions so that customers are not charged for items they didn't buy, with the help of machine learning we were able to develop a model capable of detecting fraudulent credit card transactions.

#### The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

#### This dataset is severely imbalanced (most of the transactions are non-fraud).
#### To address the problem of imbalanced dataset we have couple of techniques like undersampling, ensemble methods and oversampling data approach techniques.

#### One way the imbalance may affect our Machine Learning algorithm is when our algorithm completely ignores the minority class
![image.png](attachment:image.png)

#### undersampling: Undersampling means to get all of the classes to the same amount as the minority class or the one with the least amount of rows.

#### Example - The class column has three labels: 1, 2, and 3. Label 1 has 39 instances, label 2 has 32 instances and label 3 has 29 instances. In order to apply undersampling to the aforementioned dataset, we would have to reduce label 1 and label 2 to the same amount of instances as label 3. Thus each label would have, in this particular case, 29 instances each. 


#### Oversampling: duplicate the other classes' rows to be equal to that of the majority class.

## Good prediction results can be achieved with imbalanced datasets as well as with balanced ones. Random Forest and XGBoost Classifiers gave us the best results being able to detect more than 80% of fraud transactions and at the same time not classifying a lot of non-fraud transactions as fraud. There is no perfect model and there will always be a trade-off between precision and recall. It is up to the company and its objectives to decide which approach is the best in each particular situation
