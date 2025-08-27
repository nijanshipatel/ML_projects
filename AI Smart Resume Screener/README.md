This project demonstrates how machine learning can be applied in the health domain to predict Body Mass Index (BMI) based on lifestyle factors. The model is implemented in PyTorch and serves as a simple proof-of-concept for health-related risk assessment.

📌 Objective

Predict a person’s BMI using:

Sleep Hours – daily sleep duration

Daily Steps – number of steps walked each day

Calorie Intake – daily calorie consumption

📊 Dataset

A small, dummy dataset was created with 15 samples.

Each record contains three input features (Sleep, Steps, Calories) and one target variable (BMI).

Example data:

Sleep_Hours	Daily_Steps	Calories_Intake	BMI
7	7000	2200	23
6	5000	2000	24
⚙️ Model & Training

Framework: PyTorch

Model: Linear Regression → nn.Linear(3,1)

Optimizer: Stochastic Gradient Descent (SGD, lr=0.01)

Loss Function: Mean Squared Error (MSELoss)

Training: 500 epochs with decreasing training loss

🚀 Workflow

Data Preparation → Dummy dataset creation

Feature Selection → Sleep, Steps, Calories

Model Definition → Linear Regression in PyTorch

Training → Loss minimization using SGD

Evaluation → Assessing model fit on BMI predictions
