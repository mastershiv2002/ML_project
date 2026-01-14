💧 Water Potability Prediction Using Supervised Machine Learning
📌 Project Type

Mini Project – Supervised Machine Learning

📌 Abstract

Access to clean and safe drinking water is a major global challenge. Water quality depends on several chemical and physical parameters, and manual testing is often time-consuming and expensive.
This project focuses on predicting whether water is potable (safe for drinking) or non-potable using supervised machine learning algorithms. By analyzing various water quality parameters, the model helps in early detection of unsafe water and supports data-driven decision making.

📌 Problem Statement

Determining water potability through traditional laboratory methods requires time, resources, and expertise. There is a need for an automated system that can analyze water quality parameters and accurately predict whether the water is safe for human consumption.

Objective:
To build a supervised machine learning model that predicts water potability based on physicochemical properties of water.

📌 Dataset Description

Dataset Name: Water Potability Dataset

Source: Kaggle

Total Records: 3276

Total Features: 10

🔹 Input Features

pH

Hardness

Solids

Chloramines

Sulfate

Conductivity

Organic Carbon

Trihalomethanes

Turbidity

🔹 Target Variable

Potability

0 → Water is not drinkable

1 → Water is drinkable

📌 Tools & Technologies Used

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

IDE / Platform: Jupyter Notebook

📌 Methodology

Data Collection – Imported dataset from Kaggle

Data Exploration – Statistical analysis and visualization

Data Preprocessing

Handling missing values using median imputation

Feature scaling using StandardScaler

Data Splitting

Training Set: 75%

Testing Set: 25%

Model Training

Applied supervised learning algorithms

Model Evaluation

Accuracy

ROC-AUC Score

Confusion Matrix

Precision, Recall, F1-Score

📌 Machine Learning Algorithms Used

Logistic Regression

Decision Tree Classifier

📌 Performance Metrics

Accuracy: 70%

ROC-AUC Score: 64%

The model performs reasonably well, though prediction accuracy is affected by missing values and class imbalance.

📌 Results & Analysis

Logistic Regression provided stable performance

Decision Tree captured non-linear relationships

ROC curve indicates moderate classification capability

Class imbalance impacted recall for potable water

📌 Conclusion

This project demonstrates the application of supervised machine learning in predicting water potability. Although the model achieved moderate accuracy, it proves that machine learning can assist in water quality assessment and help identify unsafe drinking water efficiently.

📌 Limitations

Dataset contains missing values

Class imbalance between potable and non-potable samples

Limited number of features

📌 Future Scope

Apply advanced algorithms like Random Forest and XGBoost

Use SMOTE to handle class imbalance

Hyperparameter tuning for better accuracy

Deploy the model as a web application using Flask or Streamlit

📌 References

Kaggle Water Potability Dataset

Scikit-learn Documentation

Research papers on water quality analysis
