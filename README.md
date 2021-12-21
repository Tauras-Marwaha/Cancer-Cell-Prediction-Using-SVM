# Cancer-Cell-Prediction-Using-SVM

SVM or Support Vector Machine is a supervised Machine Learning technique. It is used for classification, regression, and outlier detection.

1.	SVM Demo – Breast Cancer Data Set
Use SVM to build and train a model using human cell records and classify cells to whether the samples are benign (mild state) or malignant (evil state).

SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable (This gets done by kernel function of SVM classifier). A separator between the categories is found, then the data is transformed in such a way that the separator could be drawn as a hyperplane.

2.	Perform Necessary Imports

3.	About the Data Set
Public Source: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original) 
UCI Machine learning repository

4.	Load Data from CSV File : The characteristics of the cell samples from each patient are contained in fields Clump to Mit. The values are graded from 1 to 10, with 1 being the closest to benign. The Class field contains the diagnosis, as confirmed by separate medical procedures, as to whether the samples are benign (value = 2) or malignant (value = 4).

5.	Distribution of the classes

6.	Selection of unwanted columns

7.	Remove unwanted columns

8.	Divide the data as Train/Test dataset

9.	Modelling (SVM with Scikit-learn)

10.	Evaluation (Results)
