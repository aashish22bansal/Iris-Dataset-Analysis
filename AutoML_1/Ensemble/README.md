# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model      |   Weight |
|:-----------|---------:|
| 11_Xgboost |       12 |

### Metric details
|           |   0 |         1 |         2 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----:|----------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |   1 |  0.928571 |  1        |   0.973684 |    0.97619  |       0.975564 | 0.0714492 |
| recall    |   1 |  1        |  0.923077 |   0.973684 |    0.974359 |       0.973684 | 0.0714492 |
| f1-score  |   1 |  0.962963 |  0.96     |   0.973684 |    0.974321 |       0.973645 | 0.0714492 |
| support   |  12 | 13        | 13        |   0.973684 |   38        |      38        | 0.0714492 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |               12 |                0 |                0 |
| Labeled as 1 |                0 |               13 |                0 |
| Labeled as 2 |                0 |                1 |               12 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
