# autoML
Library for automating machine learning experiments. Still in development. See 'cls_experiment.py' for example experiment definition.

Features:
* Single function wrapper for performing classification and regression on arbitrary data, collecting results, and saving to disk.
* Library of model definitions drawn from scikit-learn and wrapped with hyperparameter search optimizers (GFS, Hyperband, Bayesian)
* Allows arbitrary definition of cross-validation functions
* Allows arbitrary definition of data transformers and feature selectors

In Development:
* Automate hyperparameter optimization of feature generation/selection parameters
* Enhanced figures and reporting
