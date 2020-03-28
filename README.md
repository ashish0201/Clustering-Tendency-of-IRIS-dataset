# Clustering-Tendency-of-IRIS-dataset

##Summary
###According to the research paper quoted:
#####A value for H higher than 0.75 indicates a clustering tendency at the 90% confidence level.
The null and the alternative hypotheses are defined as follow:
Null hypothesis: the dataset D is uniformly distributed which means no meaningful clusters.,
Alternative hypothesis: the dataset D is not uniformly distributed which means it contains meaningful clusters.
If the value of Hopkins statistic is close to 1, then we can reject the null hypothesis and conclude that the dataset D is significantly a clusterable data.
When the above code is run multiple times on the IRIS Dataset, the Hopkins Statistic consistently evaluates to more than 0.8. (It differs everytime as the random uniform distribution gives different values in each run),
Thus we can safely that the IRIS Dataset is highly clusterable and hence has high clustering tendency.
