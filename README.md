# ML Presentation

Team Choice: Classification

__Joshua Staples__

Model: GBT 

Accuracy: 75%

Precision: 83% (0's) 55% (1's)

F1-Score: 83% (0's) 55% (1's)

Does really good identifying 0's, barely better than a guess for 1's. 

Excluded the >100000 Income column.

ROC Curve:

![](./img/download.png)

__Kody Smith__

Model: GBT 

Area Under ROC Curve: 79.79%

Accuracy: 77.2%

Precision: 0's: 78.56% 1's: 71.08%

F1-Score: 0's: 85.17%  1's: 52.52%

Excluded the >100000 Income column.

ROC Curve:

![](./img/ROC_curve_ks.png)

<!-- __Bryton Petersen__

Model: SVM Classifier

Accuracy:

Precision:

F1-Score:

![](I dont actually have a picture yet)
 -->
 
 __Matthew Goodsell__
 
Model: Random Forest Classifier
 
Area Under ROC Curve: 77.9%

Accuracy: 76.7 % 

Precision on 0s: 80.12% 1s: 61.75%
F1 Score     0s: 84.85% 1s: 49.65%

 
Excluded the >100000 Income column.

 
![](./img/rf_roc_plot_mg.png)


### Final Model

Random Forest Classifier with 77.9 Area Under ROC Curve

Model's parameters: 
- Number of trees set to 15
- Max Depth of the trees set to 15

Top ten most important Features

![](./img/feature_importance.png)
