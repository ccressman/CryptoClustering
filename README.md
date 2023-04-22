This repository utilizes unsupervised machine learning to analyze price changes for crypocurrencies over various time periods, including 24hours, 7 days, 14days, 30 days, 60 days, 200 days, and 1 year. 

After scaling the data using the StandardScalar module from scikit-learn, a KMeans clustering model was used to determine the optimal number of clusters that should be used to group the data. Additionally, Principal Component Analysis was then used as a technique to best differentiate the dataset's data points. The three principal components used represented almost 90% of explained variance. 

Based on the elbow and scatter plots generated using KMeans and PCA, one can conclude that using less features of the data results in a similar level of performance to the original model as four clusters are clearly illustrated in both.

![composite_elbow](https://user-images.githubusercontent.com/119253324/233811863-86fabe31-a022-4537-84e2-a2c6fe13ae57.png)

![composite_scatter](https://user-images.githubusercontent.com/119253324/233811912-5036eabf-b691-4d0f-94c8-b343e0cbe570.png)

