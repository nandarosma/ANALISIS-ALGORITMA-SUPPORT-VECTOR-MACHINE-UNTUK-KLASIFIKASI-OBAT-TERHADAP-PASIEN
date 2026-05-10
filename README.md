# Analisis Algoritma Support Vector Machine Untuk Klasifikasi Obat Terhadap Pasien
-Project Overview

This project implements a Machine Learning model using the Support Vector Machine (SVM) algorithm to classify drug types based on patient medical data. The system is designed to support healthcare decision-making by predicting the most appropriate drug category for patients using data-driven analysis.

The model analyzes several medical attributes such as age, gender, blood pressure, cholesterol level, and sodium-to-potassium ratio to determine the suitable drug classification.

This project was developed using Python and Google Colab as part of a research study in the field of Artificial Intelligence and Healthcare.

-Research Publication

This project has been published in the Journal of Information and Technology (JIDT) 2025.

Publication Title:
Precision Medicine Through Support Vector Machines: Analyzing Patient Data for Improved Drug Classification

https://jidt.org/jidt/article/view/627

-Objectives

The main objectives of this project are:

1. To implement the Support Vector Machine (SVM) algorithm for drug classification
2. To improve the efficiency and accuracy of drug recommendation processes
3. To demonstrate the application of Artificial Intelligence in healthcare systems
4. To analyze patient medical data using Machine Learning techniques

-Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Google Colab, Jupyter Notebook

-Dataset

The dataset used in this project was obtained from a public dataset available on GitHub and contains 200 patient records for drug classification analysis.

The dataset includes the following features:

1. Age
2. Sex
3. Blood Pressure
4. Cholesterol
5. Na_to_K Ratio
6. Drug Category

-Data Collection

The dataset was imported and analyzed to understand the structure, attributes, and target labels.

![Pickup by Hour](monthly_charges_Data Collection.png)

-Data Preprocessing

Data preprocessing was performed to ensure the dataset quality before model training:

Checking missing values
Removing duplicated data
Data cleaning
Feature preparation

-Data Transformation

Categorical features such as gender, blood pressure, and cholesterol level were transformed into numerical values using Label Encoding.

-Train-Test Split

The dataset was divided into:

80% training data
20% testing data

This step helps evaluate the model performance on unseen data.

-Model Training

The Support Vector Machine (SVM) algorithm was used to train the classification model.

SVM was selected because of its strong performance in classification tasks and its ability to handle multidimensional datasets effectively.

-Model Evaluation

The model performance was evaluated using:

Confusion Matrix
Accuracy Score
Precision
Recall
F1-Score
