# PCA-embedded-Random-Forest
This will include the source code and a comparison of RF-PCA and traditional random forests using twenty random parameter sets. 

File Viewing
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Github can have problems viewing .ipynb file if this happens get the sharable link from RF-PCA.ipynb and paste it into the search bar of
https://nbviewer.jupyter.org/.

Project Description
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This projects focuses on unsupervise feature contruction to improve the preformance of the random forest algorithm for imbalenced datasets. 
The programs included a from scratch implementation of random forest as well as implementation using the scikit-learn decision tree class. 
PCA will be used to create unique new feature within each tree which is generated using feature randomness. Each tree with in the PCA-embedded
Random Forest tracks a PCA model which is later used to transform the test data. RF-PCA resulted in models which favored high precision
making it useful in some applications. 
