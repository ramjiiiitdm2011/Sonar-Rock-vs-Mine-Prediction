🔊 Sonar Rock vs Mine Prediction

This project uses Machine Learning to classify objects detected under the sea as either a Rock or a Mine based on sonar signals.
The model is trained on the Sonar Dataset (UCI Machine Learning Repository) and implemented in Google Colab using Logistic Regression.

📌 Project Overview

🌊 Problem Statement: Correctly identify whether sonar signals reflect from a metal cylinder (mine) or a rock under the sea.

🤖 Approach: Preprocess sonar data, split into train/test sets, train a Logistic Regression classifier, and evaluate performance.

📊 Goal: Assist in automatic detection of underwater objects, which is useful for defense and marine applications.

📂 Dataset

Name: Sonar Dataset

Source: UCI Machine Learning Repository

Shape: 208 rows × 60 features + 1 label

Labels:

M → Mine

R → Rock

⚙️ Workflow

Data Collection – Load dataset into Pandas DataFrame.

Data Preprocessing – Explore dataset, check distributions, and separate features & labels.

Train-Test Split – 90% training, 10% testing (stratified).

Model Training – Logistic Regression from scikit-learn.

Model Evaluation – Accuracy on training and test data.

Predictive System – Build a simple input system to classify new sonar readings.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Environment: Google Colab

📈 Results

Training Accuracy: ~83%

Testing Accuracy: ~76%

The model generalizes well and can be improved further with advanced algorithms (e.g., SVM, Random Forest, Neural Networks).

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/Sonar-Rock-vs-Mine-Prediction.git


Open the notebook in Google Colab or Jupyter.

Run all cells to train the model and test predictions.

🎯 Outcome

A Logistic Regression model that can classify sonar signals as Rock (R) or Mine (M), achieving reliable accuracy and providing a baseline for future improvements in underwater object detection.
