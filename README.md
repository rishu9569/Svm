# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)](https://archive.ics.uci.edu/ml/datasets/Shill+Bidding+Dataset#)

Number of Instances: 6321

Number of Attributes: 12

## Final Result Table
<img width="530" alt="Screenshot 2023-04-20 at 1 52 29 AM" src="https://user-images.githubusercontent.com/119438568/233191236-4d2d5c7e-85ae-4cc5-bca2-da4439928037.png">



## Convergence Graph
<img width="854" alt="Screenshot 2023-04-20 at 1 48 44 AM 1" src="https://user-images.githubusercontent.com/119438568/233190423-4acae69c-da44-4216-9e28-44d0e6b0f673.png">


## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.
The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.9 having kernel = sigmoid, Nu = 1.38 and Epsilon = 8.85.

## Written By
Name : Rishabh Puri
  
Roll No. : 102003661

Sub-Group: 3CO26
