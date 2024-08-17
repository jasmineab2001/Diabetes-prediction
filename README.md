# Diabetes-prediction




This project is focused on analyzing and predicting diabetes using the Pima Indians Diabetes Database. The analysis includes data preprocessing, exploratory data analysis (EDA), and applying machine learning models to predict the likelihood of diabetes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Diabetes is a chronic disease that occurs when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. The Pima Indians Diabetes Database is a popular dataset used for predicting the onset of diabetes based on diagnostic measures.

This project involves:
- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Building and evaluating machine learning models.
- Visualizing the results.

## Dataset
The dataset used in this project is the Pima Indians Diabetes Database. It contains several medical predictor variables and one target variable, `Outcome`, indicating whether the patient has diabetes (1) or not (0).

### Features:
- `Pregnancies`: Number of times pregnant.
- `Glucose`: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
- `BloodPressure`: Diastolic blood pressure (mm Hg).
- `SkinThickness`: Triceps skinfold thickness (mm).
- `Insulin`: 2-Hour serum insulin (mu U/ml).
- `BMI`: Body mass index (weight in kg/(height in m)^2).
- `DiabetesPedigreeFunction`: A function that scores the likelihood of diabetes based on family history.
- `Age`: Age (years).
- `Outcome`: Class variable (0 or 1).

## Installation
To run this project locally, please ensure you have Python installed, along with the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend missingno
```

## Usage
To use the notebook, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/pima-diabetes-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd pima-diabetes-prediction
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook "PIMA diabetes blog.ipynb"
    ```

## Project Structure
- `PIMA diabetes blog.ipynb`: The main Jupyter Notebook containing code, analysis, and visualizations.
- `diabetes.csv`: The dataset used for analysis.

## Results
The project results include:
- Insights from the Exploratory Data Analysis (EDA).
- Performance metrics of various machine learning models.
- Visualizations for better understanding the data and model predictions.

## Contributing
If you would like to contribute to this project, please fork the repository and create a pull request. Your contributions are welcome!
