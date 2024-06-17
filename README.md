# Challenge Module 11
## Crypto_Clustering: An ASU AIML Challenge by CA Frisby

The exercise:  Cryptocurrency data that includes the names of different crypto 
and price changes over multiple time intervals is analyzed for grouping patterns
or "clusters".  The data is clustered by scaling data and utilizing two
different clutering methods, K-means and principal component analysis (PCA).

This ASU AI / ML Bootcamp Challenge is divided into eight steps, as follows:

* Step 1: Set up the repository.  The repository includes this markdown file,
the main code file "Crypto_Clustering", and a data file "crypto_market_data.csv"
in the "Resources" Folder.

* Step 2: Prepare the data.  The StandardScaler() Module from scikit-learn was
used to scale or normalize the data.  The normalized data was then used to
create a dataframe of the data for further analytics.

* Step 3: Find the best value for "k" using the original scaled dataframe.
An elbow curve is plotted to determine the best value of k or number of 
clusters.

* Step 4: Cluster using K-Means
Using the ideal k value determined from the elbow curve, a model with clusters
is fit using the scale data from Step 2.

* Step 5:  Optimize Clusters with PCA
The original scaled data from Step 2 is used to perform a PCA.  The
explained variance is reviewed to determine how much information is attributed
to each principal component, for a total of 3 principal components.

* Step 6:  Find the Best Value for "k" using the PCA Data
Similar to Step 3, an elbow curve is plotted from the inertia values generated
with the PCA data.  

* Step 7:  Cluster with K-Means and PCA data
Similar to Step 5, predict the clusters to group. Then graph the clusters with 
the x-axis as PC1 and y-axis at PC2.

* Step 8:  Determine Principal Component Weights.
Using pca.components_.T and the original scaled dataframe, the weights of each
feature for each principal component are calculated, returned, and reviewed.

## Results
For the seven time intervals examined, the three most predictive time periods
across 3 PCA groupings were price change over 200 days, 30 days and 7 days. 

Please note this is a fictional project for classroom training.


## References
Code for this challenge is supported by class activities from Module 11.