# 🍷 Wine Quality Prediction — Complete ML Project

## Overview

This project implements a machine learning model to predict wine quality using physicochemical properties. The task is formulated as a binary classification problem, categorizing wines as either "GOOD" (quality score ≥ 7) or "BAD" (quality score < 7).

## Dataset

- **Source**: Wine Quality Dataset (Red Wine)
- **File**: `winequality.csv`
- **Features**: 11 physicochemical properties (e.g., fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol)
- **Target**: Quality score (0-10), binarized to GOOD/BAD
- **Size**: 1599 samples

## Models Implemented

The project compares multiple machine learning algorithms:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree Classifier**

Models are evaluated using metrics: Accuracy, Precision, Recall, F1-Score.

## Key Features

- **Data Preprocessing**: Handling missing values, feature scaling
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical analysis
- **Model Training**: Train-test split, hyperparameter tuning with GridSearchCV
- **Model Evaluation**: Comprehensive metrics and confusion matrices
- **Feature Importance**: Analysis of most influential features

## Installation

### Prerequisites

- Python 3.7+
- Jupyter Notebook

### Dependencies

Install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Or if using npm (as per package.json):

```bash
npm install
```

## Usage

1. **Clone/Download** the project files.

2. **Place** `winequality.csv` in the project directory.

3. **Open** the Jupyter notebook:

   ```bash
   jupyter notebook wine_ml_project_3.ipynb
   ```

4. **Run** all cells in sequence to:
   - Load and explore the data
   - Preprocess features
   - Train and evaluate models
   - View results and feature importance

## Project Structure

```
wine_ml_project/
├── wine_ml_project_3.ipynb    # Main Jupyter notebook
├── winequality.csv            # Dataset
├── package.json               # Dependencies (npm format)
└── README.md                  # This file
```

## Results Summary

- **Best Model**: [Determined by notebook execution - typically Decision Tree or Logistic Regression]
- **Performance**: F1-Score ~0.8-0.9 (varies with data split)
- **Key Features**: Alcohol, Sulphates, Volatile Acidity

Run the notebook to see detailed results, confusion matrices, and visualizations.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is for educational purposes. Dataset source: UCI Machine Learning Repository.

## Acknowledgments

- Dataset from UCI ML Repository
- Built with scikit-learn, pandas, matplotlib, seaborn