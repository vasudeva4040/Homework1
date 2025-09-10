
Linear Regression: Gradient Descent vs Normal Equation
CS5710 Machine Learning – Homework 1
University of Central Missouri
Department of Computer Science & Cybersecurity
Fall 2025

Student Information
Name: N.Vasudeva Reddy (700782257)

Course: CS5710 Machine Learning

Assignment: Homework 1, Question 7

Overview
This repository contains the Python implementation for linear regression using both the closed-form Normal Equation and Gradient Descent as required in Homework 1.
It compares the parameter estimates and visualizes both approaches on synthetic data generated as 
y=3+4x+ϵ
y=3+4x+ϵ, where ϵ is Gaussian noise.

Files
linear_regression.py: Main Python script containing code for:

Data generation

Closed-form solution

Gradient descent solution

Plots for the fitted lines and the loss curve

README.md: This file

(Optional): Jupyter notebook (.ipynb) if you choose

How to Run
Clone the repository:

text
git clone <your_repo_url>
Navigate to the folder:

text
cd <repo_folder>
Run the script:

text
python linear_regression.py
Results
Both Gradient Descent and the Normal Equation yield similar intercepts and slopes, showing successful convergence.

****The intercept is approximately 2.85 and the slope is approximately 4.05 for the closed-form linear regression solution on the synthetic data.****

The script generates two plots:

Raw data points, closed-form fitted line, and gradient descent fitted line.

MSE loss curve for Gradient Descent across iterations.
