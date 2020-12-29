# Machine Learning - Credit Card Customer Segmentation

Data analysis and ML models for Credit Card - Customer Segmentation - Clustering

1. KNN Model
2. Hierarchical Model

The KNN model was created with two approaches because the data set has a lot of outliers. First, with real data with all outliers because those outliers are in reality part of data. The second approach is with dropping part of the outliers, which I'm no fan of, but as part of an experiment in which the goal is to concentrate on the core of customers.

### Analysis:

#### Cluster 1
Customers with lower credit limit who rarely make purchases. When they make purchases the one-off purchase are more frequent. Also occasionally they use a cash advance. This is the largest group of customers and makes up 45% of all customers.
#### Cluster 2
This cluster represents 39% of the customers. These customers are people who purchase and spend more than the cluster 1 and 3. They have an average credit limit and purchases are equally distributed between one-off purchases and installment purchases. 
#### Cluster 3
What sets these groups of customers apart from others is that these customers usually take much more cash in advance. Also, they have a higher credit limit than the previous two clusters.
#### Cluster 4
Last and the smaller cluster are the customers who have high credit limits, who spend a lot, and do all kinds of purchases. Cash in advance is not used as much as in previous clusters.
