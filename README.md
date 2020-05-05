# Titanic_Problem
# A Solution to Kaggle's Titanic Problem using Neual Nets

Link : https://www.kaggle.com/c/titanic

Prerequisites:
- NumPy
- Pandas
- Seaborn
- MatPlotLib
- Keras
- Tensorflow
- SKLearn

Steps:
- Data Preprocessing:
  - Import train and test sets.
  - Edit titles of passengers to decrease variance in titles.
  - Impute missing age values as median of speific title.
  - Impute missing fare values as median of their class and age.
  - Impute missing destination values using backfill.
  - save reformatted datasets.

- Neural Network:
  - Import reformatted datasets.
  - Check number of survivors against class, gender and destination.
  - Replace gender and embarked with numberical vallues.
  - Drop unwanted columns.
  - Scale all values to float64.
  - Break dataset into train and test.
  - Create NN Model.
  - Run Model.
  - Plot val_accuracy.
  - Accuracy achieved = 86.85%
  
- Future work
  - Tune parameters for a higher accuracy rate.
