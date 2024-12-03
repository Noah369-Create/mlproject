# End-to-End Machine Learning Project with CI/CD

This project demonstrates an **end-to-end machine learning workflow** with Continuous Integration and Continuous Deployment (CI/CD) using **GitHub Actions**. It uses Python, Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn, CatBoost, XGBoost, Flask, and Dill for creating, training, deploying, and managing machine learning models.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Setup](#setup)
- [Usage](#usage)
- [GitHub Actions - CI/CD](#github-actions---cicd)
- [Directory Structure](#directory-structure)
- [Tests](#tests)
- [License](#license)

## Project Overview

This project aims to build, train, and deploy machine learning models to solve a classification problem using popular ML algorithms like **XGBoost**, **CatBoost**, and **Logistic Regression**. The goal is to automate the model training and deployment pipeline with GitHub Actions for seamless integration and deployment.

### Workflow:
1. **Data Preprocessing** - Using `Pandas` and `Numpy` to clean and transform the dataset.
2. **Exploratory Data Analysis (EDA)** - Visualizations with `Seaborn` and `Matplotlib`.
3. **Model Training** - Training models using `Scikit-learn`, `CatBoost`, and `XGBoost`.
4. **Model Evaluation** - Using metrics such as accuracy, precision, recall, and F1-score.
5. **Model Serialization** - Saving the trained model with `Dill`.
6. **API Deployment** - Creating a REST API using `Flask` to serve the model.
7. **CI/CD Pipeline** - Automated training, testing, and deployment using **GitHub Actions**.

## Technologies Used

- **Python**: Programming language for the entire workflow.
- **Pandas**: Data manipulation and analysis.
- **Numpy**: Numerical operations.
- **Seaborn**: Data visualization.
- **Matplotlib**: Graphical visualizations.
- **Scikit-learn**: Machine learning algorithms and evaluation.
- **CatBoost**: Gradient boosting library.
- **XGBoost**: Another gradient boosting library.
- **Flask**: Web framework for API deployment.
- **Dill**: Serialization library to save and load models.

## Installation

Clone this repository and create a virtual environment.

### Clone the repository:
```bash
git clone https://github.com/yourusername/ml-cicd-project.git
cd ml-cicd-project
