# Remote Sensing Data Change Detection Challenge

## Overview

This competition leverages multi-date, multi-image remote sensing data to detect changes in global conditions using computer vision techniques. The challenge is to classify geographical areas into six distinct classes using machine learning methods, based on data prepared from satellite images.

## Competition Timeline

- **Start Date:** January 24, 2024
- **End Date:** February 17, 2024

## Classes

Participants will classify geographical areas into the following six classes:
- `0: Demolition`
- `1: Road`
- `2: Residential`
- `3: Commercial`
- `4: Industrial`
- `5: Mega Projects`

## Features

- **Geographical Features:** Data includes an irregular polygon with categorical status values for five different dates.
- **Neighborhood Features:** Urban and geographical descriptors, such as proximity to rivers and industrial areas.

## Pipeline

- **Data Preprocessing:** Convert data into a format suitable for analysis.
- **Feature Engineering:** Possible use of one-hot encoding for multi-valued columns, and calculations of area or perimeter for polygons.
- **Learning Algorithms:** Choice of algorithms may include logistic regression, SVM, decision trees, neural networks, or an ensemble approach.
- **Evaluation:** Models will be evaluated based on the mean F1-Score.

## Data Files

- `train.geojson`: Training data.
- `test.geojson`: Test data.

## Evaluation Metrics

- **Primary Metric:** Mean F1-Score.
- **Evaluation Process:** Model predictions will be evaluated on Kaggle using the test dataset. The final model assessment and leaderboard ranking will be based on the mean F1-Score of the predictions.

## Submission Guidelines

- **Submission File:** Sample submissions should follow the format in `knn_sample_submission.csv` and must include headers `Id` and `change_type`.
- **Submission Limit:** Maximum of 10 submissions per day.
- **Final Scoring:** Best score obtained during the competition period.

## Participating

1. **Prepare your model:** Use `genesis.ipynb` as the base for your solution.
2. **Evaluate locally:** Ensure your model performs well on cross-validation.
3. **Create submission:** Prepare your `sample_submission.csv` based on test predictions.
4. **Submit on Kaggle:** Upload your predictions and track your ranking on the leaderboard.

For more detailed information and resources, visit the competition's [(https://www.kaggle.com/competitions/2el1730-machine-learning-project-january-2024)](#).

