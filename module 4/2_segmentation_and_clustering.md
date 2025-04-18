# Clustering and Segmentation
Clustering and segmentation are used to identify similar observations and combine them into clusters or groups for analysis. This approach provides prediction models based on behaviors and outcomes of the groupings.

## K-means Algorithm Clustering 
K-means clustering is an unsupervised algorithm approach which clusters observations into groups without it having prior knowledge or input of relationships. The most common implementation of the algorithm uses iterative refinement to increase the confidence level of the outputs. Observations are categorized around the means of a specific data point to generate clusters of similar observations. 

The pseudocode of the algorithm is as follows:
1. Initialize k means with random values
1. For a given number of iterations, iterate through items by:
* finding the mean closest to the item
* assigning the item to the mean
* updating the mean