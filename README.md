# Disease prediction using Gradient Boosting algorithm
!Disease Prediction

## Overview
This repository contains code and resources related to my disease prediction project using the Gradient Boosting algorithm. In this project, I aimed to predict the occurrence of a specific disease based on relevant features and data.

## Table of Contents
-Introduction
-Data
-Installation
-Usage
-Results
-Contributing
-License
### Introduction
In this project, I leveraged the powerful Gradient Boosting algorithm to build a predictive model for disease diagnosis. Gradient Boosting is an ensemble learning technique that combines multiple weak learners (usually decision trees) to create a strong predictive model. It’s particularly effective for handling complex relationships in data.

Data
Dataset: You can find the dataset I used in the repository. The training data contains (2351, 25) and the testing data contains (447, 25).
Features: Glucose	Cholesterol	Hemoglobin, Platelets,	White Blood Cells,	Red Blood Cells,	Hematocrit,	Mean Corpuscular Volume,	Mean Corpuscular Hemoglobin,	Mean Corpuscular Hemoglobin Concentration,	HbA1c,	LDL Cholesterol,	HDL Cholesterol,	ALT,	AST,	Heart Rate,	Creatinine,	Troponin,	C-reactive Protein.	
Target Variable: Disease
### Installation
Clone this repository:
git clone https://github.com/Endekalu777/disease-prediction.git
cd disease-prediction

Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate

Install the required packages:
pip install -r requirements.txt

### Usage
Disease Prediction Model
This repository contains a Gradient Boosting model developed to predict diseases based on various health indicators.

### Data Preprocessing
##### Steps
##### Loading Data:

Handling Missing Values: Missing values were handled by imputing with appropriate strategies like mean or median.

### Feature Scaling:
Used StandardScaler and OneHotEncoder

Used GridSearchCV for hypherparameter tuning

### Results
The model's performance was quite impressive with a mean cross-validation accuracy of 96.21%. The features that contributed most significantly to the model's predictive power can be visualized using a feature importance plot.

### Fork the repository.
Create a new branch (git checkout -b feature/my-feature).
Commit your changes (git commit -m "Add feature") and push to the branch.
Create a pull request.
### License
This project is licensed under the MIT License - see the LICENSE file for details.Disease Prediction using Gradient Boosting Algorithm.