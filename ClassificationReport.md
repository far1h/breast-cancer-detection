Accuracy:
Accuracy is the ratio of correctly predicted instances (both true positives and true negatives) to the total number of instances. It provides an overall measure of how well the model performs.

![Accuracy](https://render.githubusercontent.com/render/math?math=%5Ctext%7BAccuracy%7D%20%3D%20%5Cfrac%7BTP%20%2B%20TN%7D%7BTP%20%2B%20TN%20%2B%20FP%20%2B%20FN%7D)

Where:
- $TP$ = True Positives
- $TN$ = True Negatives
- $FP$ = False Positives
- $FN$ = False Negatives

Precision:
Precision is the ratio of true positive predictions to the total number of positive predictions made by the model. It indicates how many of the predicted positive instances are actually positive.

![Precision](https://render.githubusercontent.com/render/math?math=%5Ctext%7BPrecision%7D%20%3D%20%5Cfrac%7BTP%7D%7BTP%20%2B%20FP%7D)

Where:
- $TP$ = True Positives
- $FP$ = False Positives

Recall:
Recall, also known as sensitivity or true positive rate, is the ratio of true positive predictions to the total number of actual positive instances. It measures how well the model identifies positive instances.

![Recall](https://render.githubusercontent.com/render/math?math=%5Ctext%7BRecall%7D%20%3D%20%5Cfrac%7BTP%7D%7BTP%20%2B%20FN%7D)

Where:
- $TP$ = True Positives
- $FN$ = False Negatives

F1-Score:
The F1-Score is the harmonic mean of precision and recall. It provides a single metric that balances both precision and recall, especially useful when the class distribution is imbalanced.

![F1-Score](https://render.githubusercontent.com/render/math?math=%5Ctext%7BF1-Score%7D%20%3D%202%20%5Ctimes%20%5Cfrac%7B%5Ctext%7BPrecision%7D%20%5Ctimes%20%5Ctext%7BRecall%7D%7D%7B%5Ctext%7BPrecision%7D%20%2B%20%5Ctext%7BRecall%7D%7D)

Where:
- Precision = $\frac{TP}{TP + FP}$
- Recall = $\frac{TP}{TP + FN}$
- $TP$ = True Positives
- $FP$ = False Positives
- $FN$ = False Negatives

