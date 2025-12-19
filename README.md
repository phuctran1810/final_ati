# Healthcare Diabetes Risk Prediction - Group 16

## 📝 Project Overview
This project focuses on predicting diabetes risk using the **BRFSS 2015** dataset. By leveraging Machine Learning and Deep Learning (MLP), we aim to identify key health indicators that contribute to diabetes and build a predictive system to assist in early medical screening.

## 👥 Team Members (Group 16)
* **Khúc Ngọc Anh** - 2201140003
* **Lê Thị Khánh Linh** - 2201140048
* **Trần Thanh Phúc** - 2201140064

## 📊 Key Findings from EDA
Based on our analysis, the most significant predictors for diabetes are:
- **BMI (Body Mass Index):** A strong positive correlation with diabetes risk.
- **GenHlth (General Health):** Patient's self-reported health status is a high-impact feature.
- **Age:** Risk significantly increases in older age brackets.

## 🤖 Models Implemented
We compared three different approaches to find the most reliable model for healthcare deployment:
1. **Multi-layer Perceptron (MLP):** Our primary Deep Learning model, optimized for binary classification.
2. **Random Forest Classifier:** Used to handle non-linear relationships and provide feature importance.
3. **Logistic Regression:** Served as the baseline model for performance comparison.

## 📈 Performance Summary
The **MLP model** outperformed others in terms of stability and **Recall** for the high-risk class. In medical screening, achieving a high Recall is crucial to ensure that potential diabetic patients are not missed during the initial phase.

## 🛠️ Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
