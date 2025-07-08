# 🚢 Titanic Survival Prediction - Machine Learning Project

This project predicts the survival of passengers on the Titanic using a Logistic Regression model. It follows a complete data science workflow including data preprocessing, feature engineering, model training, evaluation, and result submission.

## 📁 Dataset

The dataset used is the famous [Titanic dataset from Kaggle](https://www.kaggle.com/c/titanic). It includes details like passenger age, sex, class, fare, and more.

---

## 🔧 Workflow

### 1. Data Preprocessing
- Handled missing values (`Age`, `Fare`, and optionally `Embarked`)
- Encoded categorical features (`Sex`, `Embarked`) using `LabelEncoder`
- Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`)

### 2. Feature Engineering
- Selected features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`
- Target: `Survived`

### 3. Model Training
- Split training data using `train_test_split`
- Trained Logistic Regression model (`sklearn.linear_model.LogisticRegression`)

### 4. Model Evaluation
- Visualized predictions using a Confusion Matrix
- Accuracy assessed via validation set

### 5. Submission
- Predictions made on the test dataset
- Output saved to `submission.csv` in the required format

---

## 🧠 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📊 Output
- Logistic Regression model with evaluation via confusion matrix
- Final submission CSV for Kaggle

---

## ✅ How to Run
1. Clone this repository
2. Open the Jupyter notebook
3. Run all cells in order
4. The `submission.csv` file will be generated in the same directory

---

## 📌 Author
Muhammad Saad Ali
📧 saadali.499@gmail.com
🔗 GitHub Profile
🔗 LinkedIn Profile

