# Healthcare Diabetes Risk Prediction

## 1. Problem Formulation
This project aims to predict diabetes risk using healthcare survey data.
The task is formulated as a binary classification problem.

## 2. Inputs and Outputs
- Input: Health indicators (BMI, Age, GenHlth, HighBP, etc.)
- Output: Diabetes_binary (0: No, 1: Yes)

## 3. Dataset
- Number of samples: 269,131
- Number of features: 21
- Class imbalance exists

## 4. Data Preparation
- Data inspection and cleaning
- Feature scaling
- Data visualization (distribution, correlation matrix)

## 5. Model and Optimization
- Models: Logistic Regression, Random Forest, MLP
- Main model: Multilayer Perceptron (MLP)
- Optimizer: Adam
- Loss function: Binary Cross-Entropy
- Threshold tuning applied

## 6. Performance Evaluation
- Confusion matrix
- ROC curve (AUC = 0.818)
- Precision–Recall analysis

## 7. Inference
The trained model can be used to predict diabetes risk on new data.

## 8. Conclusion
The MLP model achieves high recall for diabetic cases and is suitable
for healthcare screening applications.

---

## Setup Instructions

```bash
pip install -r requirements.txt
