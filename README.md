# Pass/Fail Prediction — Logistic Regression Classification Model

## Overview

This project implements a logistic regression model to predict whether a student will pass or fail an exam based on the number of hours studied.

The goal is to demonstrate how classification algorithms can model probabilities and decision boundaries in binary outcomes.

---

## Problem Statement

Academic success is often influenced by study habits. This project aims to answer:

* Can we predict whether a student will pass an exam based on study time?
* How does study time influence the probability of passing?

---

## Data

A dataset was constructed with the following variables:

* `hours_studied`: number of hours spent studying
* `passed`: binary outcome (0 = fail, 1 = pass)

The dataset contains 8 observations representing increasing study time and corresponding outcomes.

---

## Methodology

### Data Preparation

* Data was structured using a Pandas DataFrame
* Feature (`hours_studied`) and target (`passed`) variables were separated

---

### Model

A Logistic Regression model was used to:

* estimate the probability of passing
* classify outcomes into pass (1) or fail (0)

---

### Training

The model was trained on the dataset to learn the relationship between study time and exam outcome.

---

### Prediction

Predictions were made for new inputs:

```id="x1y2z3"
Prediction for 3 hours: 0
Prediction for 6 hours: 1
```

This indicates that lower study time is associated with failing, while higher study time increases the likelihood of passing.

---

### Visualization

A scatter plot was created to show:

* study hours (x-axis)
* pass/fail outcome (y-axis)

This helps illustrate the classification boundary learned by the model.

---

## Results

The model captures a clear relationship between study time and exam success:

* Students with fewer study hours are more likely to fail
* Students with more study hours are more likely to pass

---

## Key Insights

* Logistic regression is effective for binary classification problems
* Study time has a strong influence on passing probability
* The model learns a decision boundary separating pass and fail outcomes

---

## Limitations

* Small dataset size
* Synthetic data does not reflect real-world variability
* Only one feature is considered

---

## Future Improvements

* Use real-world educational datasets
* Add more features (e.g., attendance, prior grades, sleep patterns)
* Evaluate performance using metrics (accuracy, precision, recall)
* Visualize probability curve (sigmoid function)

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## Repository Structure

```id="m4n5o6"
pass-fail-prediction/
│
├── notebook.ipynb
├── README.md
```

---

## Author

Independent project demonstrating foundational skills in classification models and data analysis.
