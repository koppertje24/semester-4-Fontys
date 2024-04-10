# Clustering

This project is used as the **week 6** exercise in a Machine Learning course.


## Exercises

First run the notebook as given to see if it loads the data correctly, after that continue with the exercise below. 

### The effect of normalization

Change the code in the Modeling section of the notebook such that `X_iris` is used instead of `X_iris_normalized` when applying `AgglomerativeClustering`. Rerun all cells above and compare the results after clustering (Inference and Evaluation). Why would comparing the values of `agglom.distances_` be a bad idea? What will you evaluate on? What are your conclusions?

- did it.

### Feature selection (revisited)

In Step 4, all four features in the dataset were selected for clustering. However, when looking at the box plot in the section Preprocessing, one may observe that the values for Petal Length and Petal Width are more distinctive per species compared to Sepal Length and Sepal Width. In the Feature Selection section, select Sepal Length and Sepal Width as features for clustering. Do the same for Petal Length and Petal Width. Compare the results after clustering.

### Implement another algorithm

Implement another clustering algorithm such as K-means or DBscan. If you use K-means, use the [elbow method](https://en.wikipedia.org/wiki/Elbow_method_(clustering)) to determine a good value for K. Compare the results with the Agglomerative clustering algorithm. You can also compare your results with the K-nearest neighbours algorithm which we have discussed before. Who can get the best result?