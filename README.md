# Ola_Ensemble-learning

## Ola Driver Churn Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raghav1saboo/Ola_Ensemble-learning/blob/main/Ola_Driver_Churn_Prediction.ipynb)

## Overview

This repository contains a Jupyter Notebook that focuses on predicting driver churn for Ola. Retaining drivers is crucial for ride-sharing services, and this project aims to identify drivers who are likely to leave the company based on their attributes and historical performance data.

The analysis utilizes machine learning techniques to understand the factors contributing to driver attrition and build a predictive model.

## Problem Statement

The goal is to predict whether a driver will leave Ola or not based on their demographics, tenure information, and historical performance data. High driver churn can negatively impact the organization, making retention efforts critical.

## Dataset

The dataset used for this project is `ola_driver.csv`.

## Column Profiling

| Feature               | Description                                                                                                                                                              |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `MMMM-YY`             | Reporting Date (Monthly).                                                                                                                                              |
| `Driver_ID`           | Unique ID for drivers.                                                                                                                                                 |
| `Age`                 | Age of the driver.                                                                                                                                                     |
| `Gender`              | Gender of the driver (Male: 0, Female: 1).                                                                                                                               |
| `City`                | City Code of the driver.                                                                                                                                               |
| `Education_Level`     | Education level (0 for 10+, 1 for 12+, 2 for graduate).                                                                                                                 |
| `Income`              | Monthly average Income of the driver.                                                                                                                                  |
| `Date Of Joining`     | Joining date for the driver.                                                                                                                                           |
| `LastWorkingDate`     | Last date of working for the driver (**Target Variable** - implicitly, based on its presence or absence).                                                              |
| `Joining Designation` | Designation of the driver at the time of joining.                                                                                                                      |
| `Grade`               | Grade of the driver at the time of reporting.                                                                                                                          |
| `Total Business Value`| The total business value acquired by the driver in a month (negative indicates cancellation/refund or car EMI adjustments).                                           |
| `Quarterly Rating`    | Quarterly rating of the driver: 1, 2, 3, 4, 5 (higher is better).                                                                                                       |

## Concepts Tested

The Jupyter Notebook explores and implements the following concepts:

* **Ensemble Learning - Bagging:** Utilizing bagging techniques to improve prediction accuracy and robustness.
* **Ensemble Learning - Boosting:** Implementing boosting algorithms to build a strong predictive model.
* **KNN Imputation of Missing Values:** Handling missing data using K-Nearest Neighbors imputation.
* **Working with an Imbalanced Dataset:** Addressing the challenges posed by an imbalanced target variable (likely more non-churned than churned drivers).

## Getting Started

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/raghav1saboo/Ola_Ensemble-learning.git](https://github.com/raghav1saboo/Ola_Ensemble-learning.git)
    ```
2.  Navigate to the repository directory:
    ```bash
    cd Ola_Ensemble-learning
    ```
3.  Open and run the Jupyter Notebook `Ola_Driver_Churn_Prediction.ipynb`.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

[Optional: Add a license if you have one, e.g., MIT License]
