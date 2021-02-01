# PCA-embedded-Random-Forest
This will include the source code and a comparison of RF-PCA and traditional random forests using twenty random parameter sets. 

File Viewing
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Github can have problems viewing .ipynb file if this happens get the sharable link from RF-PCA.ipynb and paste it into the search bar of
https://nbviewer.jupyter.org/.

Project Description
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project focuses on unsupervised feature construction to improve the random forest algorithm's performance for imbalanced datasets. The programs included a from the scratch
implementation of the random forest algorithm and implementation using the scikit-learn decision tree class. PCA will create a unique new feature within each tree, which is 
generated using feature randomness. Each tree within the PCA-embedded Random Forest tracks a PCA model, which is later used to transform the test data. RF-PCA resulted in models
that favored high precision, making it useful in some applications.
