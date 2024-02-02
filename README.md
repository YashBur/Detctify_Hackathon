# Detctify_Hackathon
Steps followed in Notebook (for financial fraud detection in trasactions):

1. First we understood the data from dataset, we have transactions details with flags whether they are fraud or not, we drawn pivot table for overall numbers in dataset
2. We computed the difference between original and destination balances after a transaction, creating binary indicators based on whether the debited amount matches the change in balance.
3. We tokenized customer names using TensorFlow's Tokenizer class and then padded the sequences to a fixed length of 1. The purpose of this process seems to be converting textual customer names into numerical representations for model input.
4. We applied Logistic Regression, Decision Tree, k-Nearest Neighbors, Support Vector Classifier (SVC), Naive Bayes (GaussianNB), and Random Forest ML algorithms and evaluated them using a cross validation method.
5. We showed a visual representation of the model's performance, breaking down the counts of true positives, true negatives, false positives, and false negatives, with an option for normalization.
6. We chose best model which has low false positive counts and winner were Naive bayes and random forest.
