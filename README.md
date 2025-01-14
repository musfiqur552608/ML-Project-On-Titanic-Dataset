# Machine Learning Model Performance Analysis

This project provides a comprehensive analysis of multiple machine learning models using the Titanic dataset. The goal is to evaluate model performance, assess overfitting and underfitting, and visualize results through various metrics and graphs.

## Project Overview

This project encompasses:

- **Data Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical features.
- **Model Training**: Training seven machine learning models, including Logistic Regression, Decision Trees, Random Forest, SVM, KNN, and Neural Networks.
- **Overfitting and Underfitting Analysis**: Analyzing how well models generalize to new data and detecting if they overfit or underfit.
- **Performance Metrics**: Evaluating models on key metrics such as **train accuracy**, **test accuracy**, and **overfitting percentage**.
- **Visualization**: Providing insightful visualizations to compare model performance and detect overfitting or underfitting issues.

## Features

- **Data Cleaning**: Handle missing values, encode categorical variables, and scale features.
- **Model Evaluation**: Train multiple models and evaluate their performance on both training and testing datasets.
- **Overfitting/Underfitting Detection**: Analyze whether a model is overfitting or underfitting based on the difference between train and test accuracy.
- **Visualization**: Present model evaluation results through bar plots to highlight key differences and patterns.

## Getting Started

### Prerequisites

To run this project locally, you will need Python and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Install Dependencies

You can install all the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


###Dataset
"https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"

##Running the Project
Clone the repository to your local machine:

git clone https://github.com/your-username/machine-learning-project.git
Navigate to the project directory:

cd machine-learning-project
Run the main script:

python machine_learning_project.py

This will:

Load the Titanic dataset
Preprocess the data
Train the machine learning models
Perform the analysis (overfitting/underfitting)
Display model evaluation results and visualizations
