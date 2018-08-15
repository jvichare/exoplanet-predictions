## Exoplanet Hunting in Deep Space 

The purpose of this project is to use [this Exoplanet time series data](https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data) provided from Kaggle, to train a machine learning model and predict whether a described star is an exoplanetstar or non-exoplanet-star from time series light intensity data.

This is mainly done as an exercise in practicing my machine learning skills, and to do something more different (and possibly more difficult) than my work on the classic regression dataset, predicting housing prices in Ames, Iowa.

**8/15 Update**: Currently have a model evaluation metric function defined, with bootstrapping and SMOTE to deal with the imbalanced dataset. Current feature engineering has ended up with 99% accuracy, 0.30 precision/0.25 recall. Further work in terms of feature engineering/parameter tuning is needed to increase precision and recall.
