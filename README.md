# Multivariate Linear Regression

This repository contains a Jupyter notebook that demonstrates the implementation of multivariate linear regression using a sample dataset. The notebook includes data preprocessing, model training, and prediction steps.

## Contents

- `Multivariate_Linear_Regression.ipynb`: The main notebook containing the code and explanations.
- `data.csv` (if applicable): The dataset used for training and testing the model.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- word2number

You can install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn word2number
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/multivariate-linear-regression.git
```

2. Navigate to the repository directory:

```bash
cd multivariate-linear-regression
```

3. Open the Jupyter notebook:

```bash
jupyter notebook Multivariate_Linear_Regression.ipynb
```

4. Follow the instructions in the notebook to run the code cells and observe the results.

## Notebook Overview

The notebook is structured as follows:

1. **Import Libraries**: Import necessary libraries for data manipulation and machine learning.
2. **Load Dataset**: Load the dataset into a pandas DataFrame.
3. **Data Preprocessing**:
   - Convert categorical data to numerical format using the `word2number` library.
   - Handle missing values.
4. **Feature Selection**: Select relevant features for the regression model.
5. **Train-Test Split**: Split the data into training and testing sets.
6. **Model Training**: Train a linear regression model using the training data.
7. **Model Evaluation**: Evaluate the model's performance using the testing data.
8. **Predictions**: Make predictions on new data.

## Sample Data

The dataset used in this notebook contains the following columns:

- `experience`: Work experience in words (e.g., 'five', 'two').
- `test_score`: Test scores of candidates.
- `interview_score`: Scores from candidate interviews.
- `salary`: Salary offered to the candidate.
