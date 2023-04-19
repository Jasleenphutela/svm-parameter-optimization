# svm-parameter-optimization
# Support Vector Machines (SVM) are widely used in machine learning for classification and regression tasks. SVMs are known for their ability to handle high-dimensional data and work well with small datasets. However, SVMs require careful tuning of their hyperparameters to achieve good performance.
In this context, let's consider the "Tamilnadu Electricity Board Hourly Readings" dataset. This dataset contains hourly readings of power consumption in Tamilnadu, India, from the year 2002 to 2017. The dataset has 14 attributes, including the date and time of the reading, and the total power consumption for that hour.

## Dataset Description

# This dataset contains Tamilnadu Electricity Board Hourly Readings.It has  real time readings for residential,commercial,industrial,agriculure,to find the accuracy consumption in Tamil Nadu Around Thanajvur. There are a total of 45781 instances in the dataset, with 5 features.


## Attribute Information
# 1)forkva
# 2)forkw
# 3)type
# 4)sector
# 5)service

## References
# UCI Machine Learning Repository:Tamilnadu Electricity Board Hourly Readings Data Set (link-https://archive.ics.uci.edu/ml/datasets/Tamilnadu+Electricity+Board+Hourly+Readings)

## result
Sample	Accuracy	Kernel	Nu	C
1	0.642	rbf	0.5	12
2	0.641	linear	0.02	100
3	0.638	poly	0.6	10
4	0.632	sigmoid	0.05	0.1
5	0.624	poly	0.01	0.1
6	0.610	linear	0.1	10
7	0.615	sigmoid	0.7	1
8	0.608	linear	6	5
9	0.606	rbf	0.1	100
10	0.601	sigmoid	0.05	100

## Convergence graph of best SVM
![output](https://user-images.githubusercontent.com/100710384/233169532-69e782ae-3edf-4f14-a824-ac6c9a89cef8.png)


