SMS Spam or Ham Classification:
Training a model to predict a given SMS as spam or ham (not spam) using Naive Bayes algorithm.

The model is trained using the 'SMS Spam Collection' Dataset provided by UCI:
https://archive.ics.uci.edu/dataset/228/sms+spam+collection

Since the dataset is imbalanced (Ham labels >> Spam labels), Stratified K-Fold Cross Validation has also been used apart from the standard model evaluation method.
