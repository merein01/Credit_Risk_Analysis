# Credit_Risk_Analysis
# Overview
For this project, we used Python to create and analyze different machine learning models to predict credit risk. We oversamepled tbe data using the RandomOverSampler and SMOTE algorithms, undersampled the data using hte ClusterCentroids algorithm, used a combined approache of over and undersampling using the SMOTEENN algorithm, and compared two machine learning models, BalanedRandomForestClassifier and EasyEnsembleClassifier, to reduce bias. We evaluated the performance of each of these models and made a recommendation if they should be used to predict credit risk.

# Results
SMOTEENN Model 

<img width="909" alt="Smoteenn Model" src="https://user-images.githubusercontent.com/105119376/187731285-079cb830-318a-4345-928a-0fd899f7af14.png">

- Accuracy score: 62%

Precision:
- For high risk: 0.01
- For low risk: 1.00

Recall:
- For high risk: 70%
- For low risk: 54%

SMOTE Model 

<img width="908" alt="SMOTE" src="https://user-images.githubusercontent.com/105119376/187731394-fa70a31e-09d9-4eef-a690-ae289a2a2564.png">

- Accuracy score: 64%

Precision:
- For high risk: 0.01
- For low risk: 1.00

Recall:
- For high risk: 62%
- For low risk: 65%

RandomOverSampler Model

<img width="905" alt="RandomOverSampler" src="https://user-images.githubusercontent.com/105119376/187731577-4428bb3d-0132-472d-8fd0-cc2779e5d727.png">

- Accuracy score: 65%

Precision:
- For high risk: 0.01
- For low risk: 1.00

Recall:
- For high risk: 61%
- For low risk: 69%

ClusterCentroids Model

<img width="905" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/105119376/187731711-54672c2d-ced8-4ad9-90eb-a8961f77d347.png">

- Accuracy score: 53%

Precision:
- For high risk: 0.01
- For low risk: 1.00

Recall:
- For high risk: 61%
- For low risk: 45%

BalancedRandomForestClassifier Model

<img width="901" alt="BalancedRandomForestClassifier" src="https://user-images.githubusercontent.com/105119376/187731778-335f5dc9-0da8-4783-9a50-d3185ed8df38.png">

- Accuracy score: 79%

Precision:
- For high risk: 0.04
- For low risk: 1.00

Recall:
- For high risk: 67%
- For low risk: 91%

EasyEnsembleClassifier Model

<img width="900" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/105119376/187731855-e645e65f-cb71-4206-b628-9214f2eccc42.png">

- Accuracy score: 93%

Precision:
- For high risk: 0.07
- For low risk: 1.00

Recall:
- For high risk: 91%
- For low risk: 94%

# Summary
For all of the models, the EasyEnsembleClassifier model is the most effective because it provides the highest score for all of the risk credit. The precision is low or none for all of the models. After performing this analyis, because of its high accuracy score of above 90%, using the EasyEnsembleClassifier model will perform a high risk loan precision as a great tool for analyzing credit risk. 
