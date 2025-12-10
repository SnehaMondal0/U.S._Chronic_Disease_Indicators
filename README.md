U.S. Chronic Disease Indicators – Machine Learning Classification Project (INT234)

This repository contains my Machine Learning project for the INT234 course, where I analyze and model the U.S. Chronic Disease Indicators dataset to classify health indicator values as High or Low. The project covers the complete end-to-end ML workflow, from data preprocessing to model evaluation and visualization.

📌 Project Overview

The objective of this project is to explore chronic disease patterns across the United States and build predictive models that can classify indicator values. The dataset includes information on diseases, states, demographic factors, and corresponding health indicators. As part of this project, I performed extensive data cleaning, label encoding, and feature scaling to prepare the dataset for machine learning.

📊 Exploratory Data Analysis (EDA)

I carried out EDA to understand trends, identify distributions, and detect outliers. Visualizations were created using Matplotlib and Seaborn, helping uncover relationships between chronic disease categories and indicator values. The analysis supported feature selection and provided insight into model behavior.

🤖 Machine Learning Models

A total of four classification models were trained and compared:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Each model was evaluated using:
✔️ Accuracy
✔️ Precision
✔️ Recall
✔️ F1-Score
✔️ Confusion Matrix Heatmaps

Additionally, the Random Forest model includes a ROC Curve and Feature Importance Plot to explain its predictive strength.

📈 Results & Insights

All models performed well, but ensemble methods like Random Forest showed more robust and stable results due to their ability to reduce variance. The project highlights how model performance changes with feature scaling, tree depth, and neighborhood size.

🛠️ Tools & Libraries

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🎯 Goal of the Project

The aim is to demonstrate practical ML skills by applying preprocessing techniques, evaluating multiple algorithms, and drawing meaningful insights from a real-world public health dataset.
