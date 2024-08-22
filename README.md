# Spaceship Titanic Kaggle Competition

Welcome to my solution for the [Spaceship Titanic competition](https://www.kaggle.com/competitions/spaceship-titanic) on Kaggle.

## Project Overview

The goal of this competition is to predict whether passengers aboard the spaceship Titanic have been transported to another dimension. The provided dataset contains 12,970 rows and 14 columns, with various features describing the passengers and their journey. By leveraging the information and uncovering hidden patterns in the data, machine learning models can be trained to predict the target variable: `Transported` (True or False).

## Approach

### 1. Exploratory Data Analysis (EDA)
- Conducted a thorough analysis to understand the distribution of data, relationships between features, and any anomalies or patterns.
- Visualized key insights to guide feature engineering and model selection.

### 2. Data Preprocessing
- Addressed missing values through imputation strategies informed by the data.
- Performed feature engineering to create new features and improve model performance.
- Categorical features were encoded.

### 3. Model Training
- Trained and evaluated three different machine learning models:
  - **RandomForestClassifier**
  - **XGBoostClassifier**
  - **CatBoostClassifier**
- Each model was initially trained with default hyperparameters and evaluated on the validation set.

### 4. Hyperparameter Tuning
- Used `GridSearchCV` to optimize hyperparameters for each model.
- The CatBoostClassifier emerged as the best-performing model after tuning.

### 5. Results
- The final optimized CatBoostClassifier achieved an accuracy score of **0.80874**, placing this solution in the top 6% (128th place out of 2,196 participants) on the Kaggle leaderboard.

## Key Features of This Project
- **Comprehensive EDA**: Insightful visualizations and analysis.
- **Robust Data Preprocessing**: Effective handling of missing values and feature engineering to enhance model performance.
- **Model Comparison**: Evaluation of multiple models to identify the best-performing approach.
- **Hyperparameter Optimization**: Fine-tuning models to achieve optimal performance.

## Project Notebook
The main analysis and model training for this project is documented in the following Jupyter notebook:

- [Jupyter notebook](notebook/Space_Kaggle2 (1).ipynb)

This notebook includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing and Feature Engineering
- Model Training and Evaluation (RandomForest, XGBoost, and CatBoost)
- Hyperparameter Tuning using GridSearchCV
- Final Model Results and Interpretation

You can view the notebook directly on GitHub or download it and run it locally.

## Repository Structure
- `notebook/`: Contains the main [Jupyter notebook](notebook/Space_Kaggle2 (1).ipynb) with code for EDA, preprocessing, and model training. 
- `data/`: [Data files](data) used in the project.
- `README.md`: Project overview and documentation.

## Conclusion
This project showcases my ability to apply machine learning techniques to a dataset, optimizing model performance through careful analysis and tuning. The CatBoostClassifier’s performance demonstrates the effectiveness of this approach.
