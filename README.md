# Diabetes-Prediction-System-EDA-with-Python

This project is a binary classification task using a dataset of female patients of Pima Indian heritage, aged 21 and above. The goal is to predict whether a patient has diabetes or not based on various medical attributes.

## 📊 Dataset

The dataset contains the following features:

- **Pregnancies**
- **Glucose**
- **BloodPressure**
- **SkinThickness**
- **Insulin**
- **BMI**
- **DiabetesPedigreeFunction**
- **Age**
- **Outcome** (Target: 1 = Diabetes, 0 = No Diabetes)

## 🧠 Model Building

- Trained multiple models and selected the best based on performance.
- Used **XGBoostClassifier** for final training after hyperparameter tuning.
- Evaluated model with metrics: Accuracy, Precision, Recall, F1 Score.
- Used **k-Fold Cross Validation** to ensure generalization.

## ✅ Results

- **Best Accuracy (Cross Validation):** ~76.95%
- **F1 Score:** ~65.5%
- **Confusion Matrix** and **Feature Importance** visualizations included.
- Glucose, Age, Insulin, and BMI were the most important predictors.

## 🔧 Techniques Used

- Data Preprocessing (Handling missing values, encoding, scaling)
- Model Evaluation (Confusion Matrix, Classification Report)
- Hyperparameter Tuning (GridSearchCV)
- Feature Importance Analysis
- Model Saving (`pickle`)
- Correlation Analysis via Heatmap
- Data Visualization (Seaborn, Matplotlib)

## 📁 Files

- `Diabetes-Prediction-System-EDA-with-Python.ipynb` – Main notebook with all steps
- `RAW DATA diabetes.csv`
- `README.md` – Project documentation

## 📌 Notes

- The dataset has estimated values for some features to replace missing values.
- The model is limited to the characteristics of the dataset (females, 21+, Pima Indian heritage).
- Further improvements could include using a more balanced dataset or testing with other models.

## 📷 Visualizations

- Feature importance bar plot
- Correlation heatmap
- Confusion matrix
