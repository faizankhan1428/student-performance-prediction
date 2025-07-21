# 🎓 Student Performance Prediction

This project uses machine learning to predict whether a student will pass or fail based on various academic and lifestyle factors such as study time, number of past class failures, absences, alcohol consumption, and more.

## 🔍 Project Goals

- Predict student outcomes (pass/fail) using historical data.
- Explore and visualize important features affecting performance.
- Train and compare machine learning models (Decision Tree, Random Forest, Logistic Regression, SVM).
- Improve accuracy with hyperparameter tuning and cross-validation.

## 📂 Dataset

The dataset comes from the [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams), containing multiple features like demographics, academic history, family background, and lifestyle habits.

## 🚀 Main Steps

1. Data Loading & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Label Encoding
4. Feature Selection
5. Train/Test Split
6. Model Training (Decision Tree Classifier)
7. Evaluation (Accuracy, Precision, Recall, F1 Score)
8. Feature Importance Analysis
9. Hyperparameter Tuning (GridSearchCV)
10. Model Comparison (Random Forest, Logistic Regression, SVM)
11. Cross-Validation
12. Save Final Model (Pickle)

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Pickle

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-prediction.git
   cd student-performance-prediction

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
jupyter notebook

## 📌 Output
The final model predicts if a student will pass and gives insights into which factors (like study time, failures, etc.) impact performance most.
