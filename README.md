# Classification_model

# Goal

Using age, income, spending score (i.e., a score based on how much they’ve spent at the store in total), and savings (i.e., how much money they have in their personal bank account)
create personas for users using different algorithms

## Key Pointers

Select a clustering method (the sklearn.cluster module has many good choices, including KMeans, DBSCAN, and AgglomerativeClustering). (Note that SciPy's scipy.cluster.hierarchy.linkage has another widely used version of the hierarchical approach.)

Which clustering procedure in this situation is "better"?
Consider the algorithm's characteristics, such as the accuracy of the output, usability, speed, interpretability, etc.

Interpret the winning model's clusters. 
Specifically,verbal description of a persona that appropriately represents each cluster is given. 
Used statistics (such as cluster means or distributions), illustrations (such as exemplary cases from each cluster), and/or visualisations (such as relative significance plots or snakeplots) for better understanding.
## Important Observations

As an unsupervised ML approach, clustering eliminates the requirement to divide the data into training, validation, and test phases or anything similar.

Since clustering is unsupervised, it is impossible to identify the "real" clusters and determine if a certain technique is "right."

A dimensionality reduction method (such as sklearn.decomposition.PCA) can sometimes be successful when used on the features prior to clustering. You can do this if you want, but since there are only four characteristics to begin with, it might not be as beneficial in this situation.
