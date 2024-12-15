## Customer Segmentation for Credit Card Marketing Ads


### Overview
Dataset is for bank in New York city. The bank has extensive data on their customers for the past 6 months. The marketing team wants to launch a targeted ad marketing campaign by dividing their customers at least 4 distinctive groups. Sample Dataset summarizes the usage behaviour of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioural variables.

### Methodology
**Data Cleaning:**

* Removed missing or duplicate values.
* Standardized data formats and types.

**Exploratory Data Analysis (EDA):**

* Investigated the distribution of variables.
* Identified correlations between variables.

**Analysis and Preprocessing:**

* Normalized numerical variables.
* Encoded categorical variables.
* Split data into training and testing sets.

**K-means Clustering:**

* Applied unsupervised learning to segment customers.
* Used the elbow method to determine the optimal number of clusters.

**Principal Component Analysis (PCA):**

* To reduced dimensionality of the dataset.
* Identified important features for clustering.

**Autoencoders:**

* Implemented to learn compressed representations of input data.
* Enhanced clustering accuracy.

### Dependencies
Python \
Libraries: pandas, numpy, matplotlib, seaborn,sickit-learn, Keras, Tensorflow

### Result

Identified four distinct customer segments based on credit card usage behavior. Each segment represents a unique group with specific characteristics.
1. First Customers cluster (Transactors): Those are customers who pay least amount of intrerest charges and careful with their money, Cluster with lowest balance  and cash advance, Percentage of full payment = 23%
2. Second customers cluster  (who use credit card as a loan ): highest balance ($5000) and cash advance (~$5000), low purchase frequency, high cash advance frequency (0.5), high cash advance transactions (16) and low percentage of full payment (3%)
3. Third customer cluster (VIP/Prime): high credit limit $16K and highest percentage of full payment, target for increase credit limit and increase spending habits
4. Fourth customer cluster (low tenure): these are customers with low tenure (7 years), low balance

 
