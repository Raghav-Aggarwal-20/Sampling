# Sampling

Assignment on Sampling for UCS654

<b>Description</b>

This assignment has a dataset regarding credit cards. It is a binary classification problem. The dataset is imbalanced and hence it is balanced by using random over sampling technique. After balancing the dataset, different sampling techniques are used and 5 different models have been applied to get the accuracy on testing set. The dataset is divided into a 25-75 ratio of testing and training set.

<b>Methodology</b>

Balancing Dataset Creating different types of samples Training different machine learning models Testing the models Analysing the Result obtained Sampling Technique Description and Sampling Size Formula

Simple Random Sampling A simple random sample is a subset of a statistical population in which each member of the subset has an equal probability of being chosen. image

Z = 1.96 (for 95% confidence)

p = 0.5

E = 0.03 (assumed 3%)

n = 1067 Stratified Sampling Stratified sampling is a method of sampling that involves the division of a population into smaller subgroups known as strata. image

Z = 1.96 (for 95% confidence)

p = 0.5

E = 0.07 (assumed 7%)

S = 2

n = 784 (392 for each class) Systematic Sampling Systematic sampling is a probability sampling method where we select members of the population at a regular interval. Samples taken on every 5th interval

Cluster Sampling Cluster sampling is a probability sampling method in which we divide a population into clusters and then randomly select some of these clusters as sample.

Rows per Cluster = 20

Number of Clusters = 28 (sqrt(n/2) where n is the total number of rows) Multi-Stage Sampling In this method we have used a combination of sampling technique, i.e. cluster and simple random. The dataset is divided into clusters and then random samples are chosen from those clusters.


<b>Final Result Table</b>


<img width="688" alt="Screenshot 2023-02-21 at 2 18 14 PM" src="https://user-images.githubusercontent.com/92255222/220294446-3aedab58-3a92-4032-97b1-27614e75afab.png">


