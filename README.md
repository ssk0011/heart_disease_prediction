# heart_disease_prediction

Fine tuning a machine learning model based on a binary classification Kaggle dataset for heart disease.

Source: https://www.kaggle.com/datasets/moazeldsokyx/heart-disease

Using the dataset, this notebook tests multiple machine learning models intended to handle smaller datasets, in order to determine which one best fits to the training data.

A second feature of the notebook is feature importance based on the logistic regression model utilized in the larger grid search implementation.

## Observations

Of the three mdoels tested, logistic regression performed the best. The other two models, nearest neighbors and decision tree, achieved 100% accuracy on the test data, heavily implying the models were overfitted after grid search. Logistic regression, meanwhile, attained a highly respectable 86%.

## Future work

Check if there are additional records to add to this dataset to further train the model on.