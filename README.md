# Detecting-Panic-Disorder
![ alt text ](https://img.shields.io/badge/license-MIT-green?style=&logo=)
![ alt text ](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)
![ alt text ](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![ alt text ](https://img.shields.io/badge/-pandas-150458?logo=Pandas&logoColor=white)
![ alt text ](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=TensorFlow&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Keras-D00000?logo=Keras&logoColor=white)

The main motive behind this notebook was to develop accurate models or frameworks for detecting panic disorder. Based on collected symptoms and demographic data of respondents a binary classification was performed using machine learning techniques. To complete this task, we developed seven diverse classification models and evaluated their performance (displayed in table). We proved that class predicting in this dataset is possible. The best solution for this problem was applying the extreme gradient boosting model.

|           | SVM      | RF       | LR       | XGB      | KNN      | SGD      | ANN      |
|-----------|----------|----------|----------|----------|----------|----------|----------|
| Accuracy  | 0.817111 | 0.965667 | 0.960694 | 0.967833 | 0.959028 | 0.843556 | 0.965139 |
| F1-score  | 0.303575 | 0.476271 | 0.242100 | 0.599030 | 0.288471 | 0.325670 | 0.476865 |
| Precision | 0.180186 | 0.645977 | 0.599469 | 0.618741 | 0.512864 | 0.198193 | 0.629263 |
| Recall    | 0.963087 | 0.377181 | 0.151678 | 0.580537 | 0.200671 | 0.912752 | 0.383893 |
| AUC       | 0.886948 | 0.684128 | 0.573651 | 0.782546 | 0.596221 | 0.876660 | 0.687064 |
| TN        | 27981    | 34202    | 34359    | 33977    | 34226    | 29008    | 34173    |
| FP        | 6529     | 308      | 151      | 533      | 284      | 5502     | 337      |
| FN        | 55       | 928      | 1264     | 625      | 1191     | 130      | 918      |
| TP        | 1435     | 562      | 226      | 865      | 299      | 1360     | 572      |
| MCC       | 0.371385 | 0.477658 | 0.288230 | 0.582614 | 0.303686 | 0.382023 | 0.475013 |
