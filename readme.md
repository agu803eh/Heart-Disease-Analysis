# Heart Disease Prediction Project

This project analyzes the `heart.csv` dataset to predict the presence of heart disease using various machine learning techniques.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)

## Overview

The goal is to build predictive models that can accurately classify whether a patient has heart disease based on clinical features. The project includes data preprocessing, exploratory data analysis, model training, and evaluation.

## Dataset

- **File:** `heart.csv`
- **Source:** [https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset]
- **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, ST depression, slope, number of vessels, thalassemia, and target (presence of heart disease).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/agu803eh/AI-Specialization.git
    cd heart-disease-prediction
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place `heart.csv` in the project directory.
2. Run the main script:
    ```bash
    python main.py
    ```
3. View results and model performance metrics in the output.

## Project Structure

```
heart-disease-prediction/
├── data/
│   └── heart.csv
├── notebooks/
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── main.py
├── requirements.txt
└── README.md
```

## Results

- Achieved high accuracy with models such as Logistic Regression, Random Forest, and SVM.
- Detailed performance metrics and visualizations are available in the `notebooks/` directory.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

