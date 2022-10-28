# Credit_Risk_Analysis
## Overview of the project

Utilizing Machine Learning statistical algorithms to make predictions based on data patterns provided on credit risk. Supervised Learning using a dataset was the choice of myself and my colleague Jill, since the data includes a labeled outcome.

Various Machine Learning models were used to train and evaluate the data. Due to the dataset used contained unbalanced data (good loans vastly outweighed fradulent loans), the models of choice were:

  - RandomOverSampler
  - SMOTE 
  - ClusterCentroids
  - SMOTEENN
  - BalancedRandomForestClassifier
  - EasyEnsembleClassifier

## Results

### Oversampling with RandomOverSampler
![Ovrsmpl Acc](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Ovrsmpl%20Accuracy.png)
- Balanced Accuracy Score of 64%

![Ovrsmpl CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Ovrsmpl%20CM.png)
- High Risk Precision of 1% and Sensitivity of 61%
- Low Risk Precision of 100% and Sensitivity of 68%
- F1 value of 2% for High Risk

![Ovrsmpl Clr](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Ovrsmpl%20Clr.png)

### Oversampling  with SMOTE

![Ovrsmpl Smt](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20acc.png)
- Balanced Accuracy Score of 65.2%

![Ovrsmpl CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20CM.png)
- High Risk Precision of 1% and Sensitivity of 67%
- Low Risk Precision of 100% and Sensitivity of 64%
- F1 value of 2% for High Risk

![Ovrsmpl CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20Clr.png)
