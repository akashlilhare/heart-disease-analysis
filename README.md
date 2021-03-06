
# heart-disease-analysis
## Predicting heart disease in a patient using machine learning.

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart diesase based on their medical attributes.

### Proble Defenation :

> **Given clinical parameters about a patient, can we predict whether or not they have disease?**

### Data source :

The original data came from the cleavland data from the UCI Machine Learning Repository. https://www.kaggle.com/ronitf/heart-disease-uci

### Sample data :
![alt text for screen readers](images/sample.png
"sample data").

### Corelation of data:
![alt text for screen readers](images/corelation-matrix.png
"sample data").

### We've tried different machine learning model for prediction :

1. Logistic Regression
2. K-Nearest Neighbours classifier
3. Random Forest classifier

#### Accuracy Scores of different models :

* Logistic Regression: 0.89
* KNM: 0.69
* Random Forest : 0.84

![comparison of different models](images/model-cmp.png
"comparison of different models").

### As Accuracy Score of Logistic Regression Classifier is higher then the other two models hence we select Logistic Regression Classifier for prediction.

#### After tuning Regression Classifier we get best parameters of :
* 'C': 0.20433597178569418 
* 'solver': 'liblinear

#### Confision Matrix for Regression Classifier :
![confusion matrix](images/confusion-matrix.png
"confusion matrix").

#### Other Matris for Regression Classifier :
![all matrix](images/conclusion-table.png
"confusion matrix").
