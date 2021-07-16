# Unit 2, Sprint 2, Module 4: Classification Metrics

## Goal for this Module:
- Tweak our model to optimize the way we repair water pumps

## The core learning objectives:
- Get and interpret the confusion matrix for classification models
- Evaluate classification mdoels using precision and rcall
- Understand the relationships between precision, recall, thresholds, and predicted probabilities.
- Get ROC AUC

## Let's get into it!

### Confusion Matrix for classification models
The plot of the *confusion matrix* is easy to interpret and see where the model may have gone wrong and helps to identify patterns in misclassification.
It is often plotted as a heatmap, where the columns represent the predicted class, rows represent the true classes, and the diagonal should be equal to the 
number of observations for each class. The confusion matrix works for any number of classes, but the plot starts to become less useful with very large number of classes.

--Confusion Matrix screenshot/code

### Classification metrics of precision and recall
For some data sets and models, simply calculating the accuracy is often not enough. If your data set has unbalanced classes, thne you might have an excellent accracy 
score that isn't actually a useful metric.

Precision is the portion of positive classifications that were actually correct. 
![equation](


### Relationships between precision, recall, thresholds and predicted probabilities

### Classification metric ROC AUC to interpret classifier model




