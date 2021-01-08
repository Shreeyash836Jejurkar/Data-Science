# Credit Card Data Clustering
---


## Overview

* The idea is to develop a customer segmentation for defining marketing strategy.
* The dataset contains the usage behaviour of about 8500+ active credit card holder over a 6 month period on the basis of 18 behavioral variable.
* Applied Principle Component Analysis.

---

## Observations


<img width="600" height="350" src="https://github.com/Shreeyash836Jejurkar/Data-Science/blob/main/CreditCard%20Data%20Clustering/plots/wcss.png">

* Using Elbow Method the value obtained for K was about to between 7 to 8 . After using Silhouette the value of k was validated to be 8.

<img width="600" height="350" src="https://github.com/Shreeyash836Jejurkar/Data-Science/blob/main/CreditCard%20Data%20Clustering/plots/cluster.png">

<img width="600" height="350" src="https://github.com/Shreeyash836Jejurkar/Data-Science/blob/main/CreditCard%20Data%20Clustering/plots/pca.png">

---

### Inferences

<img  height="400" src="https://github.com/Shreeyash836Jejurkar/Data-Science/blob/main/CreditCard%20Data%20Clustering/plots/3Dcluster.png">

* The Customers with less purchase history and less balance are the one with less credit limit. The largest group of people exist in this segment.
* The Customers with high balance and high Purchase Frequency are likely to have good credit limit. The group of people in these segment are very low as compare to other segments
