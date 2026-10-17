# Red Wine Quality Prediction

A machine-learning classification project exploring how physicochemical measurements can be used to predict red-wine quality labels.

## Workflow

1. Load and inspect the dataset.
2. Check missing values, distributions, class balance, and feature relationships.
3. Split data into training and test sets before fitting preprocessing steps.
4. Train and compare classification models using a consistent evaluation strategy.
5. Report metrics such as precision, recall, F1-score, and a confusion matrix—not accuracy alone.

## Dataset

Use the public Wine Quality dataset from the UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/186/wine+quality. Confirm the exact file and target-label handling used by this repository before reproducing results.

## Run

- Use a supported Python 3 environment.
- Install dependencies from the repository's dependency file if provided.
- Run the notebook or script included in the repository.
- Record package versions, random seeds, and the train/test split for reproducibility.

## Important notes

This is an educational modelling exercise, not a validated food-safety or commercial quality-control system. Results depend on the dataset, label definition, split strategy, and model choices. Avoid data leakage by fitting scaling or feature-selection steps on training data only.
