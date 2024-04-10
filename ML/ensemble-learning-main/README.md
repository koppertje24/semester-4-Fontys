# Optimization

This project is used as the **week 7** exercise in a Machine Learning course.


## Exercises

First run the notebook as given to see if it loads the data correctly, after that continue with the exercise below. 

### Apply Boosting

Have a look into which instances of the test set the random forest regressor has issues with (so which ones have a large error). A method to improve accuracy is to run apply boosting. One boosting method available in sklearn is [AdaBoosting](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostRegressor.html). Apply boosting and see whether the model performs better. Which of the "hard" instances have been predicted better now?

### Apply Stacking

Stacking is another way to improve our prediction model. Combine the random forest model with another machine learning model that we have covered in the past weeks by making use of the [Stacking Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.StackingRegressor.html). Evaluate the results and see whether the outcome is as you expected.

### Apply Hyperparameter Tuning

Two parameters of the random forest model are the maximum depth of the tree and the number of trees used. In the notebook it is already shown that changing the maximum depth can have quite the impact. Apply [Grid Search](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) to find good values for both parameters.