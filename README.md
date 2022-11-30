# Execution-characteristics-prediction

### File structure

preprocessing.ipynb - prepares data, merges all the collected log files into single csv
prediction.ipynb - initial notebook for testing and models examination
final_prediction_experiments.ipynb - final version of prediction with all done experiments

results of experiments are stored in /results folder. There are multiple .csv files from different experiments. Every file contains the information about the tested dataset, features version, pipeline (single-step or two-steps), regressor, prediction time and the scores measured by multiple metrics: Adjusted R^2, R^2, MAE, MAPE.
