# CryptoClustering
This repository contains the following files and folders:
  
* The Crypto_Clustering_complete.ipynb file contains the analysis for connecting to the crypto_market_data.csv file contained in the Resources folder.
The analysis answers all questions for the Module 19 Challenge.

*Resources Folder*
- Contains the crypto_market_data.csv file with data to work with.

# Questions to answer:

**Question 1:** What is the best value for `k` using the Scaled Dataframe?

* **Answer:** Looking at the elbow curve, the value of 4 sits at the bottom of the more aggresively sloped section of the graph, therefore it appears the value of 4 would be best.

**Question 2:** What is the total explained variance of the three principal components?

* **Answer:** The three components create a total explained variance of 0.895 or 89.5%

**Question 3:** What is the best value for `k` when using the PCA data?

  * **Answer:** Looking at the elbow curve, the value of 4 sits at the bottom of the more aggresively sloped section of the graph, therefore it appears the value of 4 would also be best for this data.


**Question 4:** Does it differ from the best k value found using the original data?

  * **Answer:** This does not differ from the original data, in fact the graph appears to be almost identical in slope shape, with a small change in inertia values between the two graphs.

  **Question 5:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** Using fewer features seems to create cluster groups that are tighter, or closer together, and outliers appear much farther away from the main cluster groups, highlighting their significance.