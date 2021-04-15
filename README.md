# kmeans
kmeans clustering implementation for cmput340 


# Introduction 
For this project I decided to implemented kmeans clustering.
Kmeans clustering is a form of unsupervised learning where we try to disover underlying patterns in the dataset and predict the the target labels of the dataset. 
Kmeans achieves this by clustering the data into different groups. 

# Implementation

### The dataset

For demonstration I will be using the Iris dataset provided by sklearn. The dataset contains two features; Sepal length and Sepal width and three target labels:
setosa, versicolor, and virginica. From the scatter plot we can see that these three target groups somewhat form their own clusters. With kmeans we would like to predict these same clusterings with our predicted labels. 

 <img src="iris.png"/>
 
### The Algorithm
 
The kmeans algorithm is an iterative procces which attempts to partition our dataset into k clusters where each datapoint belongs to a cluster with nearest mean.

- First we need to determine our k. for this instance we want k=3 since we have observed 3 somewhat distinct groups in the dataset. 
- Next we must
  
