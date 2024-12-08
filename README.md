# Machine Learning Assignment Project

## Overview
This project is based on machine learning algorithms and involves several stages to solve a given problem. The goal is to apply various machine learning techniques to process data, build models, and make predictions or classifications. The primary dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset.

## Dataset: Breast Cancer Wisconsin (Diagnostic)
This project utilizes the Breast Cancer Wisconsin (Diagnostic) dataset to apply machine learning algorithms for cancer diagnosis. The dataset consists of 569 instances, each with 30 numeric, predictive attributes that describe various characteristics of cell nuclei obtained from fine-needle aspirates (FNA) of breast masses.

### Data Set Characteristics:
* Number of Instances: 569
* Number of Attributes: 30 numeric attributes, plus the class label.

### Attributes:
Each instance in the dataset contains the following attributes:
+ **Mean Features:**
  - Radius (mean of distances from the center to points on the perimeter)
  - Texture (standard deviation of grayscale values)
  - Perimeter
  - Area
  - Compactness
  - Concavity
  - Symmetry
  - Fractal Dimension
+ Standard Error: Measures for radius, texture, perimeter, area, etc.
+ Worst Features: Maximum of the mean, standard error, and worst values for each feature.
These attributes describe various physical characteristics of the breast mass.

### Target Class:
The class labels are:
+ Malignant (WDBC-Malignant)
+ Benign (WDBC-Benign)

### Data Summary:
+ Missing Values: None
+ Class Distribution: 212 instances are malignant, 357 are benign.

## Objective
The objective of this project is to build a model that can classify breast cancer masses as either malignant or benign using machine learning algorithms. 
Various techniques are employed, including data preprocessing, feature selection, and model evaluation.

## Installation
1. Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/NicoleDavidov/BreastCancerMLAssignment.git
Install the required dependencies:

2. Copy code
pip install -r requirements.txt

## Usage
1. Load the dataset and preprocess it (handle missing values, normalize data, etc.).
2. Split the data into training and testing sets.
3. Train a machine learning model using algorithms like Logistic Regression, Support Vector Machine (SVM), or Random Forest.
4. valuate the model's performance using metrics like accuracy, precision, recall, and F1-score.

  
