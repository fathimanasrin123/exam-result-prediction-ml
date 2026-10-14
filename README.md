# Exam Result Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict whether a student will pass or fail an examination based on selected academic features.

The model is developed using Python and the UCI Student Performance dataset. Logistic Regression is used as the classification algorithm.

## Objectives

- Analyze student academic data.
- Prepare the dataset for Machine Learning.
- Predict Pass or Fail results.
- Evaluate the model using performance metrics.
- Visualize the results using graphs.

## Dataset

The project uses the UCI Student Performance dataset.

Selected features:
- `studytime` — Study time
- `failures` — Previous academic failures
- `absences` — Number of absences
- `G1` — First-period grade
- `G2` — Second-period grade

The target variable is `Result`:
- `1` — Pass
- `0` — Fail

The target is created using the final grade `G3`, where a grade of 10 or above is classified as Pass.

## Algorithm

**Logistic Regression**

The dataset is divided into 80% training data and 20% testing data.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Evaluation Metrics

The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Run

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` notebook.
4. Obtain the UCI Student Performance dataset and upload the required CSV file.
5. Run the notebook cells in order.

## Project Limitations

The prediction depends on the quality of the dataset and the selected features. The output is an estimate and does not guarantee a student's actual future result.

## Author

Student Machine Learning Project
