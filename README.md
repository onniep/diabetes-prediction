# Diabetes Prediction Project

This project involves analyzing a diabetes dataset and building a logistic regression model to predict the outcome (whether an individual is diabetic or non-diabetic). The project includes data visualization, data preprocessing, model training, and evaluation.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine
- The following Python libraries installed:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Project Structure

The project directory should contain the following files:

- `.ipynb_checkpoints/`: Checkpoints for the Jupyter Notebook.
- `diabetes.csv`: The dataset file.
- `Diabetes.ipynb`: The Jupyter Notebook containing the analysis and model code.
- `README.md`: This README file.

## Dataset

The dataset `diabetes.csv` used in this project is sourced from MeriSKILL. It should contain the following columns:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/onniep/diabetes-prediction.git
    cd diabetes-prediction
    ```

2. Install the required dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

## Usage

Run the script to perform the analysis and build the model:
```bash
jupyter notebook Diabetes.ipynb

