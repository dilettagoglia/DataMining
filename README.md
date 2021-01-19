# Data Mining Project
Final project for the [Data Mining Course A.Y. 2020/2021](http://didawiki.cli.di.unipi.it/doku.php/magistraleinformatica/dmi/start) @ University of Pisa
The project consists in data analysis based on the use of data mining tools.

### Learning Goals
- Fundamental concepts of data knowledge and discovery.
- Data understanding
- Data preparation
- Clustering
- Classification & Regression
- Pattern Mining and Association Rules
- Outlier Detection
- Time Series Analysis
- Sequential Pattern Mining
- Ethical Issues

### Further info:
Final grade: 30/30


# Project Description
## Task 1 Data Understanding and Preparation

Explore the dataset with analytical tools and describe data semantics, assessing data quality, the distribution of the variables and correlations.
Improve the quality of your data and prepare it by extracting new interesting features to describe the customer profile and his purchasing behavior. 
Defines additional indicators for the construction of a customer profile that can lead to an interesting analysis of customer segmentation.

Explore the new set of features for a statistical analysis (distributions, outliers, visualizations, correlations).

### Subtasks
- Data semantics
- Distribution of the variables and statistics
- Assessing data quality (duplictates, missing values, outliers)
- Variables transformations & generation
- Pairwise correlations and eventual elimination of redundant variables

## Task 2: Clustering analysis
Based on the customer’s profile, explore the dataset using various clustering techniques.
Carefully describe your decisions for each algorithm and which are the advantages provided by the different approaches.

### Preprocessing: 
High-correlated features elimination and Normalization

### Clustering Analysis by K-means
1. Identification of the best value of k
2. Characterization of the obtained clusters by using both analysis of
the k centroids and comparison of the distribution of variables within
the clusters and that in the whole dataset
3. Evaluation of the clustering results

### Analysis by density-based clustering 
1. Parametr tuning
2. Characterization and interpretation of the obtained clusters
3. Evaluation

### Analysis by hierarchical clustering
1. Compare different clustering results got by using different version of the algorithm
2. Find the optimal cut
3. Show and discuss different dendrograms using different algorithms

### Conclusions
- Final evaluation of the best clustering approach and comparison of the clustering obtained

### Optional task for clustering:
Explore the opportunity to use alternative clustering techniques in the library: https://github.com/annoviko/pyclustering 

## Task 3: Predictive Analysis 
Consider the problem of predicting for each customer a label that defines if (s)he is a high-spending customer, medium-spending customer or low-spending customer.

1. Define a customer profile that enables the above customer classification, reasoning also on the suitability of the customer profile, defined for the clustering
analysis. 
2. Compute the label for any customer. Note that, the class to be predicted must be nominal.
3. Perform the predictive analysis comparing the performance of different models discussing the results and discussing the possible preprocessing that they
applied to the data for managing possible problems identified that can make the prediction hard. The evaluation should be performed on both training
and test set.

## Task 4: Sequential Pattern Mining
Consider the problem of mining frequent sequential patterns. To address the task:
1) Model the customer as a sequence of baskets
2) Apply the sequential pattern mining algorithm
3) Discuss the resulting patterns

### Optional Task: 
Eextend the algorithm and analysis considering one
or more temporal constraints.
