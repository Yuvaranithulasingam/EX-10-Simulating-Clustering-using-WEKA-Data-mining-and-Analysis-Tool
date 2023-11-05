# EX 10: Simulating Clustering using WEKA Data mining and Analysis Tool

## Date:

## AIM:
To perform a classification technique using WEKA tool

## WEKA:
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −
image

## CLUSTERING:
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.

## PROCEDURE:

1.In the WEKA explorer select the Preprocess tab. Click on the Open file ... option and select the iris.arff file in the file selection dialog.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/b310d508-862d-442d-8540-a82e7d02251d)

2.Click on the Cluster TAB to apply the clustering algorithms to our loaded data. Click on the Choose button. Now, select EM as the clustering algorithm.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/cbaef2a1-8895-4bd0-87c9-67e34512cb9e)

3.In the Cluster mode sub window, select the Classes to clusters evaluation option
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/a27d9feb-d22e-4e6d-99c8-fd4b680ec3c7)

4.Click on the Start button to process the data. After a while, the results will be presented on the screen.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/9ba5a2cf-cb2f-4158-a263-7a51870837da)

5.From the output screen, you can observe that − There are 5 clustered instances detected in the database. The Cluster 0 represents setosa, Cluster 1 represents virginica, Cluster 2 represents versicolor, while the last two clusters do not have any class associated with them.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/dcb71e41-9679-47dc-9efd-cbb036c4474c)

6.To visualize the clusters, right click on the EM result in the Result list.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/66f119f8-d3f5-40b9-ae5c-f18974c9d699)

7.Select Visualize cluster assignments.
![image](https://github.com/Yuvaranithulasingam/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418522/b63b8e58-f8d0-4c94-b44d-ca5a2f7970fd)

## RESULT:
Thus the simulation of clustering technique has been executed using WEKA tool successfully.
