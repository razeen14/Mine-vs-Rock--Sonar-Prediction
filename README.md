# Overview
The Mine vs Rock - Sonar Prediction project aims to classify objects detected by sonar as either mines or rocks using machine learning algorithms. By analyzing sonar signals bounced off objects underwater, the model distinguishes between dangerous mines and harmless rocks, providing a useful tool for underwater exploration and naval applications.
# Features
Data Preprocessing: Handles scaling and normalization of sonar data.

Machine Learning Models: Implements Logistic Regression, and other classifiers for object prediction

Performance Metrics: Evaluates model performance using accuracy, precision, recall, and F1 score.

# Dataset
The dataset contains 60 frequency-based sonar attributes representing the echo responses of objects. Each record is labeled as either mine or rock. The dataset is split into:

Training Set: Used to train the machine learning model.

Test Set: Used to evaluate the performance of the model.

# Workflow
1. Data Loading: Load the dataset of news articles with their labels.
   
2. Data Preprocessing:
   
   -Normalize and scale features.
   
   -Split the data into training and test sets.

3. Model Training:
   
   Implement Logistic Regression for classification.

4. Evaluation:
   
   Test the model using the test set and evaluate using performance metrics.

# Installation

1. CLone the repository
   ```bash
   git clone https://github.com/razeen14/Mine-vs-Rock--Sonar-Prediction.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd Mine-vs-Rock--Sonar-Prediction
   ```
   
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   
# Usage

1. Train the model: Run the script to train the model on the provided dataset.
   ```bash
   python train_model.py
   ```

2. Evaluate the model: Evaluate the model's performance on the test data.
   ```bash
   python evaluate_model.py
   ```


