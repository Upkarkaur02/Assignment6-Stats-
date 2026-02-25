Title: Data Generation using Modelling and Simulation

1. Introduction: Machine Learning models require large and well-structured datasets. However, real-world data is often unavailable, expensive, or time-consuming to collect.
   To overcome this limitation, modelling and simulation can be used to generate synthetic datasets that resemble real-world behavior.

In this project, we use:

🔹 SimPy

SimPy is a Python-based discrete-event simulation library used for modeling queue systems, manufacturing systems, network traffic, and other dynamic processes. 2. Problem Statement: We simulate a Single Server Queue System (M/M/1 model) and generate synthetic data using different system parameters. The goal is:

- Generate 1000 simulation runs

- Create a dataset

- Apply multiple ML models

- Compare their performance

- Identify the best performing model

2. Simulation model Description: We implemented an M/M/1 queue system with:
- Random customer arrivals
- Single service counter

- Exponentially distributed service time

3. ML Models Used: We trained and compared the following regression models:

1. Linear Regression

2. Decision Tree Regressor

3. Random Forest Regressor

4. Support Vector Regressor (SVR)

5 K-Nearest Neighbors (KNN)

6. Gradient Boosting Regressor

7.Neural Network (MLP Regressor)

All models were trained using an 80–20 train-test split.
5. Evaluation Metrices:

- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)
6. Best Model
- Random forest Regressor
- Result:

<img width="374" height="307" alt="image" src="https://github.com/user-attachments/assets/a5d2e45c-f755-4950-b86d-e083fe0f4f57" />

 - Visualization Result:

   <img width="636" height="515" alt="image" src="https://github.com/user-attachments/assets/026d8cd8-c06c-4dad-a50a-cbdaef127387" />

Live Link:
https://colab.research.google.com/drive/1pbEZUWIfAXHLtBZHe3o2BmY0Z3AHbjjz#scrollTo=ya_krEc4aMz9
