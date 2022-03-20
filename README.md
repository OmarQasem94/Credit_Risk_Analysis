# Credit_Risk_Analysis


## **Analysis Overview**
This project utilized Python's imbalanced-learn and scikit-learn libraries to build and evaluate several machine learning models to predict credit risk.

The following procedures were followed to aadminister the analysis:

* Oversample the data using the RandomOverSampler and SMOTE algorithms.
* Undersample the data using the ClusterCentroids algorithm.
* Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
* Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.


## **Results**

### **RandomOverSampler Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.6367, which means that the model is successful at accuratelly predicting the credit risk 64% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.01, which means that the model accurately identifies a high risk applicant 1% of the time.
* It also yielded a high_risk recall score of 0.62, which means that the modell is successful at identiying all high risk applicants 62% of the time.
* Finally the model yields a F1 score of 0.02, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.65, which means that the modell is successful at identiying all low risk applicants 65% of the time.
* Finally the model yields a F1 score of 0.79, which is significantly higher due to the relatively closer recall and precision scores.

### **SMOTE Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.6303, which means that the model is successful at acturatelly predicting the credit risk 63% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.01, which means that the model accurately identifies a high risk applicant 1% of the time.
* It also yielded a high_risk recall score of 0.62, which means that the modell is successful at identiying all high risk applicants 62% of the time.
* Finally the model yields a F1 score of 0.02, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.64, which means that the modell is successful at identiying all low risk applicants 64% of the time.
* Finally the model yields a F1 score of 0.78, which is significantly higher due to the relatively closer recall and precision scores.

### **ClusterCentroids Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.5293, which means that the model is successful at accuratelly predicting the credit risk 53% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.01, which means that the model accurately identifies a high risk applicant 1% of the time.
* It also yielded a high_risk recall score of 0.61, which means that the modell is successful at identiying all high risk applicants 61% of the time.
* Finally the model yields a F1 score of 0.01, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.45, which means that the modell is successful at identiying all low risk applicants 45% of the time.
* Finally the model yields a F1 score of 0.62, which is significantly higher due to the relatively closer recall and precision scores.

### **SMOTEENN Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.6248, which means that the model is successful at accuratelly predicting the credit risk 62% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.01, which means that the model accurately identifies a high risk applicant 1% of the time.
* It also yielded a high_risk recall score of 0.71, which means that the modell is successful at identiying all high risk applicants 71% of the time.
* Finally the model yields a F1 score of 0.02, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.54, which means that the modell is successful at identiying all low risk applicants 54% of the time.
* Finally the model yields a F1 score of 0.70, which is significantly higher due to the relatively closer recall and precision scores.

### **BalancedRandomForestClassifier Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.7878, which means that the model is successful at accuratelly predicting the credit risk 79% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.04, which means that the model accurately identifies a high risk applicant 4% of the time.
* It also yielded a high_risk recall score of 0.67, which means that the modell is successful at identiying all high risk applicants 67% of the time.
* Finally the model yields a F1 score of 0.07, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.91, which means that the modell is successful at identiying all low risk applicants 91% of the time.
* Finally the model yields a F1 score of 0.95, which is significantly higher due to the relatively closer recall and precision scores.

### **EasyEnsembleClassifier Model**

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The RandomOverSampler Model yielded a balanced accuracy score of 0.9254, which means that the model is successful at accuratelly predicting the credit risk 93% of the time. 

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

![streets](https://github.com/OmarQasem94/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets.PNG)

* The model yielded a high_risk precision score of 0.07, which means that the model accurately identifies a high risk applicant 7% of the time.
* It also yielded a high_risk recall score of 0.91, which means that the modell is successful at identiying all high risk applicants 91% of the time.
* Finally the model yields a F1 score of 0.14, which is due to the the large disparity between the efficacy of the precision and the recall tests.

* The model yielded a low_risk precision score of 1.00, which means that the model accurately identifies a low risk applicants 100% of the time.
* It also yielded a low_risk recall score of 0.94, which means that the modell is successful at identiying all low risk applicants 94% of the time.
* Finally the model yields a F1 score of 0.97, which is significantly higher due to the relatively closer recall and precision scores.


## **Summary**

In conclusion all the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. However, the Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits. The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities. 