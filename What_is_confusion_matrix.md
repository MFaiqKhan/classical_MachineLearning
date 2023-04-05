The confusion matrix is a tool used to evaluate the performance of a classification algorithm, such as an email spam filter. 
It consists of four possible outcomes when classifying emails as spam or not spam: __true positives__, __true negatives__, __false positives__, and __false negatives__. 
True positives are emails correctly identified as spam, while true negatives are emails correctly identified as not spam. 
False positives are emails incorrectly identified as spam, and false negatives are emails incorrectly identified as not spam.

From the confusion matrix, several evaluation metrics can be calculated to better understand the performance of the classification algorithm. 
The first metric is _accuracy_, which measures the overall proportion of correctly classified emails. 
_Precision_ is the proportion of true spam emails among those classified as spam, 
while _recall (sensitivity)_ is the proportion of actual spam emails that were correctly identified as spam. 
_Specificity_ represents the proportion of actual non-spam emails that were correctly identified as non-spam.
The _F1 score_ is a single metric that balances both false alarms and missed detections, and is calculated as the harmonic mean of precision and recall. A high F1 score indicates a well-performing classification algorithm.


✅ True Positives (TP): Spam emails correctly identified as Spam.
✅ True Negatives (TN): Ham emails correctly identified as Ham.
❌ False Positives (FP): Ham emails incorrectly identified as Spam (Type I error/false alarm).
❌ False Negatives (FN): Spam emails incorrectly identified as Ham (Type II error/missed detection).

By using the confusion matrix, we can compute several evaluation metrics to better understand the performance of a classification algorithm, such as an email spam filter. These metrics include:

1. Accuracy: (TP + TN) / (TP + TN + FP + FN)
This metric represents the overall proportion of correctly classified emails (both spam and ham).

2. Precision: TP / (TP + FP)
This metric measures the proportion of true spam emails among those classified as spam. A high precision indicates a low false alarm rate.

3. Recall (Sensitivity): TP / (TP + FN)
Recall is the proportion of actual spam emails that were correctly identified as spam. A high recall means that the algorithm is effective at catching spam emails.

4. Specificity: TN / (TN + FP)
Specificity represents the proportion of actual ham emails that were correctly identified as ham. A high specificity means that the algorithm is effective at correctly classifying non-spam emails.

5. F1 Score: 2 (Precision Recall) / (Precision + Recall)
The F1 score is the harmonic mean of precision and recall, providing a single metric that balances both false alarms and missed detections. A high F1 score indicates a well-performing classification algorithm.
