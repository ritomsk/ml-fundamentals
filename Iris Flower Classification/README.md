# Iris Flower Classification

## Overview
This project focuses on the classification of Iris flowers into three distinct species: **Setosa**, **Versicolor**, and **Virginica**. The classification is performed using a machine learning approach based on four features of the flowers: sepal length, sepal width, petal length, and petal width.

## Project Structure
- `IRIS.csv`: The dataset containing 150 instances of Iris flowers with their respective feature measurements and species labels.
- `iris_flower_classification.ipynb`: A Jupyter Notebook containing the Python code for Data Exploration, Visualization, and Machine Learning modeling.

## Technologies Used
- **Python**: Programming Language
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **matplotlib** & **seaborn**: Data visualization
- **scikit-learn**: Machine learning model building and evaluation

## Workflow
1. **Data Loading**: Reading the dataset from the CSV file.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics of the dataset.
   - Grouping by species to analyze mean feature sizes.
   - Visualizations including Scatter plots, Line plots, Histograms, Heatmaps (for correlation), KDE plots, and Pairplots to understand data distributions and feature relationships.
3. **Data Preprocessing**: Splitting the dataset into features (`x`) and target variable (`y`), followed by splitting into training (60%) and testing (40%) sets.
4. **Machine Learning Modeling**: Four different classification algorithms were trained and evaluated:
   - K-Nearest Neighbors (KNN)
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Decision Tree Classifier

## How to Run
1. Make sure you have Python installed along with the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `jupyter`).
2. Open `iris_flower_classification.ipynb` in a Jupyter Notebook environment.
3. Run all cells sequentially to see the data visualizations and model evaluation scores.

## Results
The performance of each model is evaluated using the accuracy score metric on the test dataset. The notebook provides the score for each individual algorithm implemented.
