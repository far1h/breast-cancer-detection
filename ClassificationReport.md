Accuracy:
Accuracy is the ratio of correctly predicted instances (both true positives and true negatives) to the total number of instances. It provides an overall measure of how well the model performs.

$$

\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}

$$

Where:
- $TP$ = True Positives
- $TN$ = True Negatives
- $FP$ = False Positives
- $FN$ = False Negatives

Precision:
Precision is the ratio of true positive predictions to the total number of positive predictions made by the model. It indicates how many of the predicted positive instances are actually positive.

$$

\text{Precision} = \frac{TP}{TP + FP}

$$

Where:
- $TP$ = True Positives
- $FP$ = False Positives

Recall:
Recall, also known as sensitivity or true positive rate, is the ratio of true positive predictions to the total number of actual positive instances. It measures how well the model identifies positive instances.

$$

\text{Recall} = \frac{TP}{TP + FN}

$$

Where:
- $TP$ = True Positives
- $FN$ = False Negatives

F1-Score:
The F1-Score is the harmonic mean of precision and recall. It provides a single metric that balances both precision and recall, especially useful when the class distribution is imbalanced.

$$

\text{F1-Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}

$$

Where:
- Precision = $\frac{TP}{TP + FP}$
- Recall = $\frac{TP}{TP + FN}$
- $TP$ = True Positives
- $FP$ = False Positives
- $FN$ = False Negatives

