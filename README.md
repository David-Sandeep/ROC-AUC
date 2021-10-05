# ROC-AUC

In Machine Learning, performance measurement is an essential task. So when it comes to a classification problem, we can count on an AUC - ROC Curve. When we need to check or visualize the performance of  classification problem, we use the AUC (Area Under The Curve) ROC (Receiver Operating Characteristics) curve. It is one of the most important evaluation metrics for checking any classification model’s performance. It is also written as AUROC (Area Under the Receiver Operating Characteristics)

The ROC curve is plotted with TPR(True Positive Rate) against the FPR where TPR is on the y-axis and FPR(False Positive Rate) is on the x-axis.


TPR (True Positive Rate) / Recall /Sensitivity =TP/(TP+FN)

FPR=FP/(FP+TN)

An excellent model has AUC near to the 1 which means it has a good measure of separability. A poor model has an AUC near 0 which means it has the worst measure of separability. In fact, it means it is reciprocating the result. It is predicting 0s as 1s and 1s as 0s. And when AUC is 0.5, it means the model has no class separation capacity 


## Diabetes-Detection
 Goals:
* SVM and Logistic regression to predict if a patient has diabetes
* Plot ROC and compute AUC using Scikit Learn


