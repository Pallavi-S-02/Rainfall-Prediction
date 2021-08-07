# Rainfall-Prediction

A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset. This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier, etc.. Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others. Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.

## Workflow:

## Data Collection:
Dataset link is below.
 https://www.kaggle.com/jsphyg/weather-dataset-rattle-package 
 
## Data Preprocessing:
1) Missing Values Handled by Random Sample imputation to maintain the variance
2) Categorical Values like location, wind direction are handled by using Target guided encoding
3) Outliers are handled using IQR and boxplot
4) Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb
5) Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook/RainPrediction1.ipynb
6) Imbalanced Dataset was handled using SMOTE

## Model Creation:
1) Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.
2) Out of these catboost, random forest and support vector machines were top 3
3) The conclusion were made using classification metrics. roc curve and auc score.


### If you like this project please do give a star. I am also giving my LinkedIn profile. If you want we can connect there too.
https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_self_edit_top_card%3BgUAoiRPcQTGRqP8sUBqFSQ%3D%3D
