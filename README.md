# Near Earth Objects (NEO) Classification Project

This project involves the classification of Near Earth Objects (NEOs) using machine learning models. Two primary models are implemented: a Random Forest Classifier and a Decision Tree Classifier. The goal is to determine whether a given NEO is hazardous or not based on its individual features.

## Project Files

- **`nearest-earth-objects(1910-2024).csv`**: The dataset containing features of various NEOs and a target variable indicating if the NEO is hazardous (`is_hazardous`).
- **`neos_preprocessing.ipynb`**: A Jupyter Notebook for exploratory data analysis and preprocessing of the data (handling duplicates and outliers, and correcting for the imbalance in the target variable)
- **`neos_classification_tree.ipynb`**: A Jupyter Notebook implementing a Decision Tree Classifier for the same classification task.
- **`neos_random_forest.ipynb`**: A Jupyter Notebook implementing a Random Forest Classifier to predict the hazard level of NEOs.

## Models Implemented

1. **Decision Tree Classifier**
    - A simple model that uses a single decision tree for classification.
    - The dataset is split into training and testing sets.

2. **Random Forest Classifier**
    - This model uses an ensemble of decision trees to improve prediction accuracy.
    - The same dataset is used, with similar steps for training, testing, and evaluation.

## Libraries Used

The following Python libraries were used in this project:

- **pandas**: For data manipulation and analysis.
- **scikit-learn**: For model implementation, including `RandomForestClassifier`, `DecisionTreeClassifier`, `train_test_split`, and evaluation metrics.
- **matplotlib**: For visualizing the confusion matrix.
