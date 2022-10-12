# Bank Marketing Campaign

In today's cutthroat marketing environment, banks provide a variety of packages to entice clients. It would be beneficial for the banks to create a package based on a certain demography, allowing them to target those consumer groups particularly or adjust their packages as necessary. This categorization model aims to forecast whether a consumer will purchase their term deposit or not. Whereas a term deposit is a type of deposit offered by a financial institution with a fixed rate of interest that is high and an established maturity date.

### Input Data 
Dataset is from the UCI Machine Learning Repository. Features of this dataset includes:
* Age
* Job type
* Marital status
* Education
* Credit default status
* Average yearly balance
* Mortgage
* Personal loan
* Contact type
* Day of the month
* Month of the year
* Call duration
* Number of contacts
* Days since last contact
* Number of contacts
* Previous campaign outcome
* Output: Opened Term Deposit

### Model Workflow
we have built five models:
* K-Nearest Neighbor (KNN)
* Support Vector Machine (SVC)
* Random Forest (RFC)
* Gradient Boosting (GBC)
* Deep Neural Network (DNN)

 #### The data sets that we have used are imbalanced, with 88% no and 12% yes. So, Balanced data set is created for training and comparing to the imbalanced data set.
 

### Comparison of models and Results:


### Conclusion:
Deep Neural Network outperformed all other classifiers.

Balancing classes reduced accuracy but also reduced overfitting and increased recall.




