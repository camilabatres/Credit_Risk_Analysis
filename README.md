# Credit_Risk_Analysis
## Purpose 
I oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Lastly, I used two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Results 
* Naive Random Oversampling 
![image](https://user-images.githubusercontent.com/100107588/175840249-2b3d87da-a313-48ff-8700-b286708351ea.png)
Above, we have a 64.22% accuracy score, 1% precision high risk, 100% precision low risk, 63% recall high-risk, and 65% recall low-risk. 

* SMOTE Oversampling 
![image](https://user-images.githubusercontent.com/100107588/175840351-8e5c52a0-8a42-46c6-8258-e3b19ecd71d5.png)
Above, we have a 63.83% accuracy score, 1% precision high risk, 100% precision low risk, 64% recall high-risk, and 63% recall low-risk.

* Undersampling 
* ![image](https://user-images.githubusercontent.com/100107588/175840403-2ea86d7b-680e-45e3-9edb-2312a1822269.png)
Above, we have a 57.50% accuracy score, 1% precision high risk, 100% precision low risk, 64% recall high-risk, and 51% recall low-risk. 

* Combination 
* ![image](https://user-images.githubusercontent.com/100107588/175840448-b3b74317-284c-48e3-8284-c6da958ecf41.png)
Above, we have a 64.85% accuracy score, 1% precision high risk, 100% precision low risk, 72% recall high-risk, and 57% recall low-risk.
