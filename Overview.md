# Customer_Segmentation
Customer segmentation in sales entails grouping customers of a wholesale company based
on their annual buying patterns using K-Means and DBSCAN (Density-Based Spatial Clustering
of Applications with Noise) clustering algorithms. The
study employs clustering as a stand-alone tool to get insight into the wholesale company client’s
buying patterns distribution and identify customer groups with similar characteristics. The result
identifies groups of similar customer purchase characteristics and helps guide the company on
targeted marketing or promotions.

Exploratory data analysis and preparation techniques were applied to the dataset, which revealed that the company’s major annual sale is from fresh
products and groceries. The company’s clients can be roughly clustered into two groups and there are exclusive clients with higher purchasing patterns. Lastly, the attributes were scaled to yield a reliable clustering result.

# Results and Analysis
**_KMeans_**

The K-Means algorithm identified five clusters, indicating that the wholesale company clients/customers can be grouped into five based on their buying 
patterns with a silhouette score of 0.368. 

![image](https://github.com/m33nm/Customer_Segmentation/assets/54365936/fa4c94e6-2072-4945-8036-f2d98302ca0c)
Figure 1: KMeans clusters

Cluster interpretations:
o Cluster 4: regular purchases, minimal spending
o Cluster 3: very high purchase, high spending
o Cluster 2: minimal purchases, very high spending
o Cluster 1: a bit more regular purchases, more spending
o Cluster 0: regular purchases, minimal spending

**_DBSCAN_**

DBSCAN algorithm identified only two clusters, indicating that the wholesale company clients
can be segmented into two groups with similar characteristics; the regular buyers and the binge
buyers with a silhouette score of 0.748699.
![image](https://github.com/m33nm/Customer_Segmentation/assets/54365936/bff3ca53-d8a2-4fd0-92d9-8c0b996671cd)
Figure 2: DBSCAN clusters

Cluster interpretations:
o Cluster 0: regular purchases, regular spending
o Cluster -1: very high purchase, high spending

# Conclusion
The two clustering algorithms, K-Means and DBSCAN, yielded a positive silhouette coefficient in
identifying clusters of wholesale company customers with similar buying characteristics. DBSCAN
had a much higher score of 0.75, which makes it better than the K-Means algorithm with 0.37.
Although the silhouette coefficient tends to be usually higher for density-based clusters, the
DBSCAN result for the customer segmentation is best suited for the wholesale company data
because it yielded a more realistic result with reliable clusters. With this result, the company
would better understand its customers and discover opportunities for better marketing and
product development.


