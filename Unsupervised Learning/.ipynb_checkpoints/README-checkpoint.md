# Unsupervised Machine Learning Methods
In this folder, we demonstrated unsupervised machine learning methods such as K-means, hierarchical clustering, and PCA analysis. We intended to figure out
1. What is the optimal number of variables to perform K-means clustering?

2. How good is the differential pattern of gene expressions between N0 and N1 groups using unsupervised learning. 

    a. What is the best perfromance of K-mean clustering in accuracy and MCC?
    
    b. Using the set fo features selected by K-mean clustering, does hierarchical clustering seperates the two groups successfully?
    
    c. Using the set fo features selected by K-mean clustering, does PCA seperates the two groups successfully?

## Coding Files
1. The Contextualize_Kmeans.ipynb file described the necessity of reducing number of features.

2. The KMeans.ipynb file described Q1 and Q2.a.

3. The Hierarchical.ipynb file described Q2.b.

4. The PCA.ipynb file described Q2.c.


## Output Files
1. Actual Classes.png from KMenas.ipynb that use two features of highest ANOVA F-value to visualize the actual classification of the whole dataset .

2. Predicted Classes.png from KMenas.ipynb that use two features of highest ANOVA F-value to visualize the predicted classification of the whole dataset with the best K Mean clustering.


3. clustermap.png from Hierarchical.ipynb that yielded a heat map with columns representing best features and row represeting patients clustered by expression level.