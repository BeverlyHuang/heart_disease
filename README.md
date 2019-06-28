# Heart Disease Classification

By Beverly Huang

### Goal
* Predicting the presence of heart disease in the patient based on available medical records
* Enabling the healthcare organization to develop proactive medical interventions for the patient

### Conclusion
* In this project, we build classification machine learning models in Python using Heart Disease dataset.
* Four classification models (LogisticRegression, SVM, RandomForest, Auto ML) are evaluated in terms of accuracy, confusion matrix, precision, recall and ROC AUC.
* From business impact viewpoint, we choose recall as the most important metric.
* The modeling and evaluation results show that Auto ML model performs better than SVM but worse than Logistic Regression and Random Forest in terms of recall.
* Random Forest Model with GridSearch has the highest recall of 0.92. This means the model can identify 92% heart disease patients correctly.
* Deploying this model has the potential to predict the presence of heart disease in the patient with high accuracy and enable the healthcare organization to develop proactive medical interventions for the patient.
