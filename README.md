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

![SMOTE Smt](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20acc.png)
- Balanced Accuracy Score of 65.2%

![SMOTE CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20CM.png)
- High Risk Precision of 1% and Sensitivity of 67%
- Low Risk Precision of 100% and Sensitivity of 64%
- F1 value of 2% for High Risk

![SMOTE CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/SMOTE%20Clr.png)

### Undersampling with ClusterCentroids

![CC Acc](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Undrsmpl%20Acc.png)
- Balanced Accuracy Score of 52%

![CC CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Undrsmpl%20CM.png)
- High Risk Precision of 1% and Sensitivity of 57%
- Low Risk Precision of 100% and Sensitivity of 47%
- F1 value of 1% for High Risk

![CC Clr](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Undrsmpl%20Clr.png)

### Combination Over and Undersampling with SMOTEENN

![Comp Acc](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Comp%20Clr.png)
- Balanced Accuracy Score of 64%

![Comp CM](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Comp%20CM.png)
- High Risk Precision of 1% and Sensitivity of 70%
- Low Risk Precision of 100% and Sensitivity of 58%
- F1 value of 2% for High Risk

![Comp Clr](https://github.com/A-Mossa/Credit_Risk_Analysis/blob/main/Imgs/Comp%20Clr.png)
