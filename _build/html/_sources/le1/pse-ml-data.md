# Data

A data set consists of data points.

We find it useful to distinguish between two different groups of properties of a data point. The first group of properties is referred to as **features** and the second group of properties is referred to as **labels**. Roughly speaking, features are low-level properties of a data point that can be measured or computed easily in an automated fashion. In contrast, labels are high-level properties of a data points that represent some quantity of interest.

Sysonyms of features are “covariate”,“explanatory variable”, “independent variable”, “input (variable)”, “predictor (variable)” or “regressor”.

labels are somtimes called the "output (variable)" or "dependent variable" or "target" or "target variable".

There are two key properties of a dataset:

- The first property is the **sample size** m, i.e., the number of individual data points that constitute the dataset.
- The second key property is the **number of features** n that are used to characterize an individual data point.

The behaviour of ML methods often depends crucially on the ratio m/n. The performance of ML methods typically improves with increasing m/n. As a rule of thumb, we should use datasets for which m/n ≫ 1. Later we will make the informal condition m/n ≫ 1 more precise.

Understanding our data is very important. The internal structure of the data gives hints to the model we should choose. In the folowing we look at tabular data, time series, images and graphs.

But before we start loooking into diferent data, we have to be familiar with some python modules and packages that help us do the work.
