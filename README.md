# Unsupervised-Learning

I have created a model in which we find the number of optimum clusters for the given iris dataset.
Dataset can be found at "https://bit.ly/3kXTdox"

Steps to train such model :

- Firstly, import the libraries which we will be needed in this task i.e pandas, numpy, matlplotlib and sklearn.
- Load the dataset in the module.
- Assign the values to a variable to implement them in Algorithm.
- We will use K-Means Clustering Algorithm for creating clusters.
- But there can be many clusters possible so we have to find optimum number of clusters.
- We will find the inertia for all values of k and plot them against k.
- From that graph we will use elbow method and check where the change in inertia is less.
- That value of k is selected and this is the number of clusters we can form.
- Using this value of k, we will implement K-Means Clustering Algorithm on our dataset and graph them.
