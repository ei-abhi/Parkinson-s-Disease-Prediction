

# Parkinson's Disease Prediction using Random Forest Classifier

## Overview
This project aims to predict **Parkinson's disease** using machine learning techniques. A **Random Forest Classifier** is employed to classify patients as having or not having the disease based on biomedical voice measurements. **Grid Search Cross-Validation (GridSearchCV)** is used to fine-tune the hyperparameters for optimal model performance.

## Dataset
The dataset used for this project contains multiple biomedical voice measurements from individuals, with a label indicating the presence of Parkinson's disease. It includes features such as **MDVP:Fo(Hz)**, **MDVP:Fhi(Hz)**, **MDVP:Flo(Hz)**, and others.

Dataset source: [UCI Machine Learning Repository - Parkinson's Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)

## Technologies Used
- Python
- Pandas & NumPy (Data Preprocessing)
- Scikit-learn (Machine Learning Model & GridSearchCV)
- Matplotlib & Seaborn (Data Visualization)

## Process Flow
1. **Data Preprocessing:**
   - Loaded the dataset and checked for missing values.
   - Scaled the features using **StandardScaler** to improve model performance.
   - Split the dataset into **training and testing sets (80:20 ratio)**.

2. **Model Selection:**
   - Used **Random Forest Classifier** for classification.
   - Applied **Grid Search Cross-Validation (GridSearchCV)** to determine the best hyperparameters (n_estimators, max_depth, etc.).

3. **Model Evaluation:**
   - Evaluated the model using **accuracy, precision, recall, and F1-score**.
   - Plotted the **confusion matrix** to visualize classification performance.

## Results
- Achieved **high accuracy** with optimized hyperparameters using GridSearchCV.
- Random Forest outperformed baseline models due to its ensemble learning capability.
- Training and Testing Accuracies are both above **90%**.

## Future Improvements
- Try different feature selection techniques to improve model performance.
- Experiment with other classifiers like **XGBoost** and **SVM**.
- Deploy the model using Flask or Streamlit for real-time predictions.

## Contact
For any queries or collaborations, feel free to reach out at **your.email@example.com**.

---
Let me know if you need any modifications! 🚀

