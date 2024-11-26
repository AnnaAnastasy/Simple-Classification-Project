# 🍄 Mushroom Classification Project

## About the Dataset
This project uses a cleaned version of the [Mushroom Dataset for binary classification](https://archive.ics.uci.edu/dataset/848/secondary+mushroom+dataset), originally available from the UCI Library. The cleaning process involved:
- Modal imputation for missing values
- One-hot encoding for categorical features
- Z-score normalization for numerical features
- Feature selection for dimensionality reduction

### Features
The dataset contains 9 columns:
1. **Cap Diameter**  
2. **Cap Shape**  
3. **Gill Attachment**  
4. **Gill Color**  
5. **Stem Height**  
6. **Stem Width**  
7. **Stem Color**  
8. **Season**  
9. **Target Class**: Is the mushroom edible or not?

### Target Variable
- **0**: Edible  
- **1**: Poisonous  

---

## Project Overview
The goal of this project is to classify mushrooms as edible or poisonous based on their physical characteristics. It follows a structured pipeline from data understanding to machine learning model implementation.

### Workflow
1. **Installing Required Libraries**  
   Install necessary libraries using Python's package manager to set up the environment.

2. **Reading and Understanding Our Data**  
   Load the dataset and explore its structure and summary statistics.

3. **Handling Outliers**  
   Identify and handle outliers using statistical techniques to improve model accuracy.

4. **Data Visualization**  
   Use visual techniques to understand relationships between features and their impact on edibility.

5. **Data Preprocessing**  
   - Separate features and target labels for modeling.
   - Apply scaling techniques to normalize data.
   - Split the dataset into training and testing subsets.

6. **Machine Learning Models**  
   - **Logistic Regression**: A linear model used for binary classification.  
   - **K-Nearest Neighbors**: A non-parametric method to classify based on proximity to other samples.

---

## Results
Achieved high accuracy for classifying mushrooms as edible or poisonous using simple machine learning model **KNN**.

## How to Use
- Clone the repository and navigate to the project directory.
- Install the required libraries:
```
pip install pandas numpy seaborn matplotlib scipy scikit-learn
```
- Download the dataset from the [Kaggle page](https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset) and place it in the same directory as the project.
- Open the notebook and execute cells sequentially to reproduce the results.
