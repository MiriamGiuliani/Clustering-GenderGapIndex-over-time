# Clustering-GenderGapIndex-over-time

This project was completed together with my college classmate Paula Costa Fontichiari. 

In this project, we dove into the main clustering algorithms with the goal of clustering time series data. Because of the complex dimension of the objects we wanted to treat, we challenged ourselves in adapting the main approaches present in the literature to this peculiar problem. 

First, we started by applying Kmeans, Kmedoids, and Hierarchical clustering algorithms, adapting them to the problem by exploiting DYNAMIC TIME WARPING as a distance metric, instead of the standard Euclidean approach. 

In the second half of the project, we focused on a Bayesian Non-Parametric Approach, applying a **Dirichlet Process Mixture Model**, after decomposing the time series objects of our data sets. This was done by following the approach in *Nieto-Barajas, Luis & Contreras, Alberto. (2014). A Bayesian Nonparametric Approach for Time Series Clustering. Bayesian Analysis. 9. 147-170. 10.1214/13-BA852*. 

All the algorithms were tested on a real data set, obtained from Gender Gab Yearly reports by the World Economic Forum. 
