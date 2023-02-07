# Wine Quality Ordinal Regression Competition
<br>
<b>Goal:</b> Predict the wine quality from given ingredients composition<br>
<br>
<br>

![cover photo](https://raw.githubusercontent.com/Masterx-AI/Project_Wine_Quality_Investigation/main/wq.jpg "wine quality")

<br>
<br>
<b>Description:</b><br>
We are given ingredients of the wine and their quantity in appropriate units; and we are expected to predict the quality of the wine.<br>
<br>
This a supervised machine learning problem where labeled data is provided. There are around 12 features and 1 target variable. The target variable is the quality of wine and ranges from 3 to 8. Also the data is imbalanced in nature having more datapoints for quality 5 & 6 and least datapoints for 3.<br>
<br>

This repository contains many different approaches used to tackle the problem. These include stacking & blending models, threshold optimization, autoMl, feature engineering, etc. The code for final selected model is present in `threshold_tunning_optuna.ipynb` notebook.<br>
<br>
<b>Evaluation metrics:</b> Quadratic Weighted Kappa (QWK)
<br>
<br>
<br>

## Results:
<br>
<b>Final model:</b> Ensemble of XGBoost & LightGBM
<br>
<b>Achieved score:</b> 0.60
<br>
