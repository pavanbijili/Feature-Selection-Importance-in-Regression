📊 Student Marks Prediction
🎯 Feature Selection Impact using F-Regression

This project demonstrates how feature selection affects model performance by comparing RMSE and R² score before and after feature selection using F-Regression (ANOVA F-test) with a Linear Regression model.

🚀 Project Objective

✔ To build a regression model
✔ To evaluate RMSE and R² score BEFORE feature selection
✔ To apply F-Regression for feature selection
✔ To evaluate RMSE and R² score AFTER feature selection
✔ To prove that feature selection improves model performance

🧠 Dataset Information

📄 File: Students2.csv

📥 Input Features

Hours

sHours

hoursplayed

income

distance

calories

🎯 Target Variable

Marks

📊 Exploratory Data Analysis (Before Split)

Before splitting the data:

Scatter plots are drawn between each feature and Marks

This visually shows the strength of relationships

Helps justify feature selection logically

🔴 Model 1: Before Feature Selection

All features are used

Linear Regression is trained

Evaluation metrics:

RMSE

R² score

📌 This acts as the baseline model

🔍 Feature Selection Technique

F-Regression (ANOVA F-test) is applied to all features.

Interpretation:

📈 High F-score → strong relationship

📉 Low p-value (< 0.05) → significant feature

✅ Selected Features

Hours

sHours

🟢 Model 2: After Feature Selection

Only selected features are used

Linear Regression is retrained

Evaluation metrics are recalculated

📌 Performance is compared with the baseline model.

📈 Model Evaluation Metrics
Metric	Meaning
RMSE	Measures prediction error (lower is better)
R² Score	Measures variance explained (higher is better)

⚠️ Accuracy is not used because this is a regression problem.

📊 Results Comparison
Metric	Before FS	After FS
RMSE	Higher ❌	Lower ✅
R²	Lower ❌	Higher ✅

✔ Feature selection reduced error
✔ Feature selection improved generalization

📉 Visualization

Actual vs Predicted Marks plot after feature selection

Points close to diagonal indicate a good fit

🛠️ Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

▶️ How to Run the Project
pip install -r requirements.txt
jupyter notebook


Open:

FeatureSelection.ipynb

✍️ Author

Bijili Pavan
🎓 Graduate 2025 | AIML Enthusiast

⭐ If you find this project helpful, feel free to star the repository!
