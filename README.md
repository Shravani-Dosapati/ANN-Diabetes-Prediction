# ANN-Diabetes-Prediction
A Deep Learning project using Keras to predict the onset of diabetes based on diagnostic measures.
# 🩸 Diabetes Prediction using Artificial Neural Networks (ANN)

This project builds a Deep Learning model to predict whether a patient has diabetes based on diagnostic measurements like Glucose level, BMI, and Insulin.

## 📊 Project Overview
- **Goal:** Binary Classification (Diabetic vs. Non-Diabetic)
- **Dataset:** Pima Indians Diabetes Dataset (768 examples)
- **Tech Stack:** Python, TensorFlow/Keras, Pandas, Scikit-Learn, Optuna

## 🛠️ Key Steps taken in Analysis
1. **Data Preprocessing:**
   - Handled missing values (zeros in Glucose/BP/Insulin) using **KNNImputer**.
   - Scaled features using **RobustScaler** to handle outliers.
2. **Baseline Model:** Built a simple ANN to establish a benchmark.
3. **Optimization:**
   - Tuned Hyperparameters (Layers, Neurons, Learning Rate) using **Optuna**.
   - Prevented overfitting with **Dropout** and **EarlyStopping**.
4. **Final Model:**
   - Addressed Class Imbalance using **Class Weights** (improving recall for diabetic cases).

## 📈 Results
- **Final Accuracy:** ~77-80%
- **Recall (Sensitivity):** Improved using class weights to minimize missed diabetic cases.
- **Confusion Matrix:** (Upload your image here)

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook `Diabetes_Prediction_ANN.ipynb`.
