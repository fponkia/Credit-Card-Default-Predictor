# Credit-Card-Default-Predictor
This project uses simple ML algorithms such as Random Forest Classifier, SVM-RBF, Decision Tree, and Logistic Regression to predict if a particular person will be defaulting on their credit card payment next month or not.

Trained the model using the data of more than 30,000 Clients with their historical data using the simple ML algorithms. Utilized the advantages of data visualization and matplotlib to get insight into each feature of the data along with understanding, which features are useful or not to train.

Utilized the features of the optimization tools such as GridSearchCV and RandomizedSearchCV to conduct hyperparameter (parameters needed by the model) optimization to achieve an improvement of 10% in the precision, ensuring the model is more robust.

Used recall as a metric of measurement instead of precision or accuracy, as a default on the credit card payment is more harmful for the companies that issued it, compared to correctly predicting as many examples as the model wants. Thus, with recall, the false negative rate is maintained as low as possible.

Achieved the recall of 74% for the SVM-RBF model. Thus, making sure that the model is as robust as possible to get a score of as low as possible for the false negative cases along with achieving a reasonably high precision score.
