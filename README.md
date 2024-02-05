# CryptoClustering
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.


Analysis:

**Question 1:** What is the best value for `k`?

**Answer:** The best value for k is 2. We know this because at 2 clusters, we can visuazlly see that this is where the elbow curve begins to level out. This is because the intertia is beginning to slow down. 

**Question 2:** What is the total explained variance of the three principal components?

**Answer:** The total explained variance of the 3 principal components is 99.38%. 

**Question 3:** What is the best value for `k` when using the PCA data?

**Answer:** 2 is the best value for k when using the PCA data. 

**Question 4:** Does it differ from the best k value found using the original data?

**Answer:** No, the results from using the PCA data do not differ when compared with the best k value found when using the original data. 

**Question 5:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

**Answer:** The impact of using fewer features to cluster the data using K-Means is that the intertia descrease and the data points appeared to be less dispesred (or more tightly clustered). When we have fewer features to cluster the data, this seems to reduce ambiguity and in turn lends itself to better interpretation of results. 
