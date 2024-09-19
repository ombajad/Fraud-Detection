# Fraud-Detection
DETAILS FOR USE OF XGBClassifier Model for Fraud Transactions
The model used for Fraud Detection is 'XGBClassifier' as it helps get better performance in prediction as the recall values are better than the 'Random Forest Classifier'.

Features like transaction amount, balance before and after transactions and the transaction type are the key criteria used to predict the Fraud Transaction.

Model is trained with adjustments of weights as the data is imbalanced in the favour of non-fraudulent transactions as they outnumber the fraud records by a huge margin.

Confusion Matrix provides the insights into th true positive (fraud detected correctly) and false negative(fraud missed).

Precision: Indicates proportion of fraud predictions that are correct.

Recall: This tells us the actual fraud cases detected by the model.

F1-Score: A harmonic mean of Recall and Precision that balances measure.

Indications for Fraud are large transaction amounts where frauds usually happen at a high amount. Transaction types like "CASH_OUT" and "TRANSFER" are the two types where frauds are seen as it is easy to liquify the amount. Sudden changes in someone's balance could also be an alarm as legitimate users don't deplete their accounts suddenly.

Preventing frauds could be done by real-time monitoring of data by installing fraud detection alerts. Strengthening security with protocols like multi factor authentication for the high amount transactions.

To check how effectively model works we can deploy and monitor its working, establish a system where false positives(non-fruadulent transactions classified as fraud) and false negatives (fraudulent transactions missed) are reviewed and analyzed for continuous improvement.
