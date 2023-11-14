# Homework 5

## Team Members
- Gurkeerat Bains - Email: bainsg21@students.ecu.edu
- Cristian Figueiredo - Emial: FigueiredoC21@students.ecu.edu

## Quick Start
- $git clone https://github.com/BainsGarry/CSCI4120.git
- cd CSCI4120/Homework5
- jupyter notebook

## Dependencies
- Python
- Numpy
- Scikit-Learn
- Scipy
- Pandas

## Hyperparameters Used

For the RandomForestClassifier, the following hyperparameters were used in the grid search:

- `n_estimators`: Number of trees in the forest. Values tried: [100, 150].
- `max_depth`: Maximum depth of the tree. Values tried: [None, 30].
- `min_samples_split`: Minimum number of samples required to split an internal node. Value used: 2.
- `criterion`: The function to measure the quality of a split. Value used: 'gini'.

## Model Performance

- **Average Accuracy**: 96.13%
  - This accuracy score reflects the overall effectiveness of the model in classifying breast cancer cases.

- **Average Accuracy per Feature**: 0.0534
  - This metric represents the average contribution of each selected feature to the model's accuracy. It is calculated by dividing the average  accuracy by the number of features (18) selected from the dataset.
