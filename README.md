# Bankruptcy-Detection

## Introduction
- Bankruptcy Detection is a kind of Anomaly detection, which can identify of rare items or suspicions, widely applied for fraud detection, structural defect, medical problems detection and so on. 
- The dataset is about bankruptcy prediction of Polish companies. The bankcrupt companies were during the period 2000-2012, while the still operating companies were from 2007 to 2013. This data was created by Sebastian Tomczak. (source: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data or https://www.kaggle.com/datasets/bhadaneeraj/bankruptcy-detection)
- The target of this project is to find a suitable machine learning model with high score. AUC, accuracy, precision, recall, f1 will be tested and the hyperparameter optimization for model is to achieve the highest "roc_auc" Score.

Five scores are used in this project:

- AUC:AUC ranges in value from 0 to 1. A model whose predictions are 100% wrong has an AUC of 0.0; one whose predictions are 100% correct has an AUC of 1.0.

- Accuracy: (TN+TP) / (TN+FP+FN+TP)

- Precision: TP / (FP+TP), typicall for cancer detection, which is also important for bankruptcy prediction. We care about not missing any positive case, thus precision is important.

- Recall:TP/(TP+FN), also named as sensitivity, means returning most of the relevant results 

- F1: 2*TP /(2*TP+FP+FN) which includes precision and sensitivity

## Content
#### A) Data Exploration
#### B) Data Pre-processing
#### C) Model Selection
#### D) Feature engineering 
#### E) Results & Discussion
#### F) Limitations
