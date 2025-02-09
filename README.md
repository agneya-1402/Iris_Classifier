# Iris Classification

This project implements an **Iris Classification** model using **Support Vector Machine (SVM)**. It involves loading the dataset, performing exploratory data analysis, and training a model to classify iris flowers into three species: *Setosa, Versicolor, and Virginica*.

## Dataset
The dataset used is the classic **Iris dataset**, which consists of 150 samples with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Each sample is labeled as one of three classes: *Setosa, Versicolor, and Virginica*.

## Project Workflow
1. **Load Data:** The dataset is read from a CSV file into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA):**
   - Summary statistics
   - Data visualization using Seaborn pairplots
   - Bar plots showing average feature values for each class
3. **Data Preprocessing:**
   - Separating features and target labels
   - Splitting into training and testing sets
4. **Model Training:**
   - Using **Support Vector Machine (SVM)** from Scikit-learn
   - Training the model on the training dataset
5. **Model Evaluation:**
   - Accuracy calculation on test data
   - Predictions for new samples

## Requirements
To run this project, install the required dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Running the Project
Run the Jupyter Notebook to execute all steps:
```bash
jupyter notebook Iris_Classification.ipynb
```

## Results
The trained model successfully classifies iris species with high accuracy using SVM.

## Author
Agneya Pathare
