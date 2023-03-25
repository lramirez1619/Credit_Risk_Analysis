# Credit_Risk_Analysis
Supervised Machine Learning and Credit Risk

**Overview of the loan prediction risk analysis:**
The purpose of this analysis is to evaluate different types of machine learning models to determine which is better at predicting credit risk. Each model will determine the accuracy score, the confusion matrix and imbalanced classification report. 

**Results:**

**Naive Random Oversampling**<end>

Accuracy score for the model is calculated:  <end>
  
![image](https://user-images.githubusercontent.com/115942978/227731461-c7ea2f81-a649-4049-b05b-77f87c7fbf7b.png)<end>

Confusion matrix has been generated<end>
  
![image](https://user-images.githubusercontent.com/115942978/227731467-3ee15b1f-d5dd-4e0f-95f5-f4e7d7ceaf04.png)<end>

Imbalanced classification report has been generated <end>
  
![image](https://user-images.githubusercontent.com/115942978/227731482-f8f5b565-0c3e-41aa-8800-d05c4e6e53c1.png)<end>

**SMOTE Oversampling**
  
Accuracy score for the model is calculated<end> 
  
![image](https://user-images.githubusercontent.com/115942978/227731497-f56ede3f-6ed2-47d6-aeb9-b251326a8494.png)<end>
  
DConfusion matrix has been generated<end>
  
![image](https://user-images.githubusercontent.com/115942978/227731513-d8732c3a-da10-4ef1-9a0f-71254a969557.png)<end>
  
Imbalanced classification report has been generated<end> 
![image](https://user-images.githubusercontent.com/115942978/227731521-e1521bd1-a12e-40ec-87ac-0784449327bc.png)<end>

**Cluster Centroids**
  
Accuracy score for the model is calculated 
  
![image](https://user-images.githubusercontent.com/115942978/227731548-c2548c46-9337-486c-b433-effa1819e832.png)
  
Confusion matrix has been generated
  
![image](https://user-images.githubusercontent.com/115942978/227731564-ad599771-1a2b-42ec-9c09-12bec0c6f8ff.png)
  
Imbalanced classification report has been generated 
  
![image](https://user-images.githubusercontent.com/115942978/227731589-048f2f48-4073-4836-8b01-2af737eca2e2.png)

**SMOTEENN**
  
Accuracy score for the model is calculated 
  
![image](https://user-images.githubusercontent.com/115942978/227731613-769bba1d-5fde-4ae7-850e-eabdf4a377ce.png)

Confusion matrix has been generated
  
![image](https://user-images.githubusercontent.com/115942978/227731630-9d3eea2e-24cd-4366-8a9e-d1c239d6207a.png)
  
Imbalanced classification report has been generated 
  
![image](https://user-images.githubusercontent.com/115942978/227731637-cd395daa-0bd3-431a-8651-5433fd897945.png)

**Balanced Random Forest Classifier**
  
Accuracy score for the model is calculated 
  
![image](https://user-images.githubusercontent.com/115942978/227733737-cd089def-ed31-4004-8868-c8c485e53677.png)
 
Confusion matrix has been generated
  
![image](https://user-images.githubusercontent.com/115942978/227733747-46ce3c9e-cf9f-4ce8-b765-a9a02ddb05f3.png)
  
Imbalanced classification report has been generated 
  
![image](https://user-images.githubusercontent.com/115942978/227733759-8396e0e3-73a1-446c-8a8b-a79a30d56b7c.png)

**East Ensemble Classifier**
  
Accuracy score for the model is calculated 
  
![image](https://user-images.githubusercontent.com/115942978/227733774-3e7768db-d9c9-453a-8153-8a8dc954fc36.png)
  
Confusion matrix has been generated
  
![image](https://user-images.githubusercontent.com/115942978/227733784-91de1247-530e-409b-9029-db09234a92fe.png)
  
Imbalanced classification report has been generated 
  
![image](https://user-images.githubusercontent.com/115942978/227733788-6d943a8c-6d29-46bc-8f76-26c12f43c188.png)

**Summary: **
  
Overall, the EAST ensemble classifier model is most effective when used to combine the predictions of various base classifiers in order to increase the precision, resilience, and reliability of the classification system.
