# TrafficEvents


In this project, the dataset file stored in Google Drive was first extracted and then loaded using the **dask.dataframe** library. After cleaning the data and taking a sample, I detected outliers using the **Z-score** method.

**Z-score**

The Z-score method detects outliers by measuring how many standard deviations a data point is from the mean. Values with |Z| greater than a chosen threshold (I chose 2 here) are considered outliers. This helps identify unusually distant points in normally distributed data.


