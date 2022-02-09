# Credit_Risk_Analysis

# Analysis Overview 

The purpose of the analysis is to predict whether a person would be a credit risk. In order to determine the risk, a dataset was used from Lending Club. In this analysis, different techniques were used to assess for the risk. First, I oversampled the data using Random Over Sampler and SMOTE algorithms, then used a combination approach of over and undersampling using the SMOTEENN algorithm. Finally, I used Balanced Random Forest Classifier and Easy Ensemble Classifier to predict credit risk. 


# Results 
* In the Naïve Random Oversampling model, the balance accuracy score is 64.7%, the precision was 99% but the recall was 55%. 

<img width="914" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/91230916/153273537-47790858-1f8a-4913-8900-023e91f1cd6b.png">


* In the SMOTE Oversampling model, the balance accuracy score is 66.2%, the precision was 99% but the recall was 69%. 

<img width="914" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/91230916/153273604-f4f1f7e7-7296-4561-873c-9ff3845e37bd.png">


* In the Cluster Centroids Undersampling model the balance accuracy score was 54.2%, the precision was 99% but the recall was 42%. 

<img width="914" alt="Cluster Centroids-Undersampling" src="https://user-images.githubusercontent.com/91230916/153273636-db401fc1-166e-4835-95f6-e60bea9ded6b.png">


* In the SMOTEENN Over and Undersampling model, the balance accuracy score was 64.0%, the precision was 99% but the recall was 58%. 

<img width="914" alt="SMOTEENN-Over and Under Sampling" src="https://user-images.githubusercontent.com/91230916/153273763-ac1981de-ce30-4fec-8f9c-f550989bdd00.png">


* In the Balanced Random Forest Classifier model, the balance accuracy score was 78.9%, the precision was 99% and the recall was 87%. 

<img width="914" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/91230916/153273828-72766b52-d26d-4679-99ab-95d133905360.png">


* In the Easy Ensemble Classifier model, the balance accuracy score was 93.2%, the precision was 99% and the recall was 94%. 

<img width="914" alt="Easy Ensemble Classifier" src="https://user-images.githubusercontent.com/91230916/153273862-99245194-4aa0-4e54-a193-84bba65e54f4.png">


# Summary
The results above show that in the first four models we used oversampling, undersampling, and a combination both to predict which model was better at predicting credit risk. In all four models the balance accuracy scores, and recall were low even though the precision was high. However, the balanced random forest classifier and easy ensemble classifier model both showed better accuracy score with precision and recall scores. In order to determine the best model to use to predict credit risk, we would want a model that has a good balance for precision and recall, which was demonstrated with the easy ensemble classifier model. The Easy Ensemble Classifier model would be the model recommended to use because it’s balance accuracy score, precision and recall score were all high, showing a good balanced. 
