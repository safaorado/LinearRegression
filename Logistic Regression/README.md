Breast Cancer Classification using Logistic Regression
A machine learning project that classifies breast mass tumors as malignant or benign based on cell feature characteristics using Logistic Regression.

Project Overview
This repository performs binary classification on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The pipeline encompasses data preprocessing, exploratory data analysis, standard feature scaling, model training using Logistic Regression, and performance evaluation.

Dataset Information
The model uses the data.csv dataset, which includes computed features from digitized images of fine needle aspirates (FNA) of breast masses:

Target Variable: diagnosis (M = Malignant, B = Benign)

Features: 30 continuous feature columns capturing radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension (across mean, standard error, and worst-case metrics).

Identifier: id (removed during preprocessing)

Metadata Column: Unnamed: 32 (removed due to null values)

Tech Stack & Dependencies
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn



