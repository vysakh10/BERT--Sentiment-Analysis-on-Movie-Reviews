# BERT--Sentiment-Analysis-on-Movie-Reviews-DataSet

A multi class classification problem in which the model predicts whether a movie review is positive, negative or neutral.

Models Used:

1. BERT
2. Logistic Regression
3. Neural Network

The features from the first token ([CLS]) is used as features to the Logistic Regression and the Neural Network Model. The FF layer of a BERT model has 768 units, therefore we will obtain a feature set of 768 dimensions.

Best Performing Model ---> BERT Features + NN
Without major hyperparameter tuning, the model gives an AUC score of 0.83. A much rigorous hyperparameter tuning might yield much better results.
