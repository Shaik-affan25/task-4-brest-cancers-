# Breast Cancer Prediction Using Logistic Regression

## 📌 Project Overview
This project uses Logistic Regression, a machine learning algorithm, to predict whether a breast tumor is malignant (cancerous) or benign (non-cancerous).

The project uses the Breast Cancer Wisconsin dataset available in Scikit-learn.

## 🎯 Objective
To build a binary classification model using Logistic Regression and evaluate its performance using different classification metrics.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Dataset
The Breast Cancer Wisconsin dataset contains 569 samples and 30 numerical features describing characteristics of breast tumors.

**Target Classes:**
- `0` – Benign
- `1` – Malignant

## ⚙️ Project Workflow
1. Import the required Python libraries.
2. Load the Breast Cancer Wisconsin dataset.
3. Explore the dataset and check for missing values.
4. Separate features and target variables.
5. Split the dataset into training and testing sets (80:20).
6. Standardize the features using StandardScaler.
7. Train the Logistic Regression model.
8. Make predictions on the test dataset.
9. Evaluate the model using classification metrics.
10. Visualize the confusion matrix and ROC curve.
11. Tune the classification threshold and compare precision and recall.

## 🧠 Algorithm: Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for binary classification.

It uses the sigmoid function to convert a linear score into a probability between 0 and 1.

**Sigmoid Function:**

σ(z) = 1 / (1 + e^(-z))

The default classification threshold is 0.5:
- Probability ≥ 0.5 → Predict Malignant
- Probability < 0.5 → Predict Benign

## 📈 Evaluation Metrics
The model is evaluated using the following metrics:

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures how many predicted malignant cases are actually malignant.
- **Recall:** Measures how many actual malignant cases are correctly identified.
- **F1-Score:** Combines precision and recall into a single metric.
- **Confusion Matrix:** Displays correct and incorrect predictions.
- **ROC-AUC:** Measures the model's ability to distinguish between malignant and benign cases.

## 📉 Visualization
The project includes the following visualizations:
- Confusion Matrix Heatmap
- ROC Curve
- Precision and Recall Comparison at Different Thresholds

## 🚀 Installation

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
