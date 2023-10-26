# Ensemble_method_software_defect_prediction
In this notebook I explore how to create an ensemble classifier and how to hypertune the underlying models. The ensemble uses a variety of tree-based models (random forest, extra random trees, XGBoost, HistBoost, CatBoost, LightGBM) as well as a neural network. The model also uses a hill-climbing approach for determining the weights of the ensemble.

Whilst I have carried out some exploratory data analysis this is not the main focus of this notebook and should be explored further at a later date.

The overall aim of the model is to try to predict whether a piece of software will have any defects based on certain characteristics.
