# 🩺 Diabetes Prediction Project

This project aims to predict the onset of diabetes in patients using machine learning models. The dataset used for this project is sourced from Kaggle and contains several medical predictor variables and one target variable, indicating whether the patient has diabetes.

## 📚 Introduction

This project uses various machine learning algorithms to predict the likelihood of a patient having diabetes based on medical test results and demographic data. The models are evaluated based on accuracy and other performance metrics to find the best predictive model.

## 📊 Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which includes the following features:
- 🟠 Pregnancies
- 🟠 Glucose
- 🟠 BloodPressure
- 🟠 SkinThickness
- 🟠 Insulin
- 🟠 BMI
- 🟠 DiabetesPedigreeFunction
- 🟠 Age
- 🟠 Outcome (target variable: 0 for non-diabetic, 1 for diabetic)

## 🔧 Preprocessing

Preprocessing steps include:
- Loading the dataset.
- Handling missing values by replacing zeros with median or mean values of the respective columns.
- Transforming features using `QuantileTransformer` to ensure consistent scaling.

## 📈 Exploratory Data Analysis

Exploratory Data Analysis (EDA) includes:
- Checking the structure and summary statistics of the dataset.
- Visualizing the correlations between features.
- Plotting distributions and density functions of features based on the target variable.

## 🤖 Modeling

Several machine learning models are used in this project:
- 🌳 Decision Tree Classifier
- 📉 Logistic Regression
- ✨ Support Vector Classifier (SVC)
- 🚀 AdaBoost Classifier
- 🌟 Gradient Boosting Classifier
- 🌳 Random Forest Classifier
- 🤝 K-Nearest Neighbors Classifier

Cross-validation is performed to evaluate model performance, and hyperparameter tuning is done using Grid Search.

## 📊 Evaluation

Models are evaluated based on accuracy, precision, recall, and F1-score. The best-performing model is selected based on these metrics and further analyzed.

## 💻 Installation

To run this project locally, ensure you have Python installed and follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/dinesh-fullstackwebdeveloper/prediction-of-diabetes-using-ml.git
   ```
2. Navigate to the project directory:
  ```bash
   cd prediction-of-diabetes-using-ml
  ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
## 🚀 Usage

To execute the analysis and modeling steps, run the Jupyter Notebook or Python script provided in the repository:

```bash
jupyter notebook diabetes.ipynb
```
## 📋 Results

The results of the analysis and the best-performing model's performance metrics are summarized in the final sections of the notebook/script. The Logistic Regression model with tuned hyperparameters showed the highest accuracy.

## 🤝 Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.



   
